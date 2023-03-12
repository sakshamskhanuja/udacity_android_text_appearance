## Text Appearance

### About

The application shows a ```TextView``` whose <b>color</b> and <b>size</b> are updated by
the ```android:textAppearance``` attribute.

```xml
<?xml version="1.0" encoding="utf-8"?>
<TextView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools" android:layout_width="wrap_content"
    android:layout_height="wrap_content" android:text="@string/description"
    android:textAppearance="@style/TextAppearance.Important" tools:context=".MainActivity" />
```

Following is the <b>style</b> used for ```android:textAppearance```:

```xml
<!-- Text Appearance for TextView -->
<style name="TextAppearance.Important" parent="TextAppearance.AppCompat">
    <item name="android:textColor">@color/color_text</item>
    <item name="android:textSize">@dimen/text_size_default</item>
</style>
```

### Screenshots

| Device      | Virtual | OS        | API | Orientation                                                                                                         |
|-------------|---------|-----------|-----|---------------------------------------------------------------------------------------------------------------------|
| Pixel 6 Pro | Yes     | Android Q | 29  | [Portrait](https://user-images.githubusercontent.com/122201501/224092909-240b911c-8f96-49c2-b80b-183c2c3fd2e2.png)  |
| Pixel 6 Pro | Yes     | Android Q | 29  | [Landscape](https://user-images.githubusercontent.com/122201501/224092887-2831f50c-78eb-470a-8788-abbe909870b8.png) |
