## offline dinosaur game in android app (Rayhan Rafi)

the trex runner game extracted from chrome offline err page.


[go and enjoy! :smile: ](http://wayou.github.io/t-rex-runner/)

![chrome offline game cast](assets/screenshot.gif)

### Step 1.
- First download the Source file and past it inside app >> assets.
```bash


```


### Step 2.
- Add the code in your activity
```bash

  <WebView
        android:id="@+id/gameView"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        />

```


### Step 2.
- Add the code in your activity java file
```bash

 
       WebView gameView = findViewById(R.id.gameView);

        gameView.getSettings().setJavaScriptEnabled(true);
        gameView.loadUrl("file:///android_asset/index.html");
        gameView.requestFocus(View.FOCUS_DOWN);

```

