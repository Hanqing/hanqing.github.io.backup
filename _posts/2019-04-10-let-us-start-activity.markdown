---
layout: post
title:  "Android技术栈-四大组件!"
date:   2019-04-10 08:43:59
author: Hanqing
categories: life
cover:  "/assets/instacode.png"
---

###RTFC – Read The Fucking Code  

- Activity启动

{% highlight java %}    
    /**
     * @hide
     */
    @Override
    public void startActivityForResult(
            String who, Intent intent, int requestCode, @Nullable Bundle options) {
        Uri referrer = onProvideReferrer();
        if (referrer != null) {
            intent.putExtra(Intent.EXTRA_REFERRER, referrer);
        }
        options = transferSpringboardActivityOptions(options);
        Instrumentation.ActivityResult ar =
            mInstrumentation.execStartActivity(
                this, mMainThread.getApplicationThread(), mToken, who,
                intent, requestCode, options);
        if (ar != null) {
            mMainThread.sendActivityResult(
                mToken, who, requestCode,
                ar.getResultCode(), ar.getResultData());
        }
        cancelInputsAndStartExitTransition(options);
    }
{% endhighlight %}