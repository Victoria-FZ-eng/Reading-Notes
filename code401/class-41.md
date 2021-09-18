# Intent Filters

Specifying the appropriate intent filter in your activity and adding specific actions.

ex: 
```
<activity android:name="ShareActivity">
    <intent-filter>
        <action android:name="android.intent.action.SEND"/>
        <category android:name="android.intent.category.DEFAULT"/>
        <data android:mimeType="text/plain"/>
        <data android:mimeType="image/*"/>
    </intent-filter>
</activity>
```

To handle intents in an activity :
1. getIntent()
2. getData()
3. setResult()
4. finish()





Reference:

* [Intent Filters](https://developer.android.com/training/basics/intents/filters)