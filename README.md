# CountDown
 
```java
new CountDownTimer(30000, 1000) {

    public void onTick(long millisUntilFinished) {
        tv.setText("seconds remaining: " + millisUntilFinished / 1000);
        //here you can have your logic to set text to edittext
    }

    public void onFinish() {
        tv.setText("done!");
    }

}.start();
```


---

```
Copyright 2021 M. Fadli Zein
```