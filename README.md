# Pemrograman Mobile - Pertemuan 5 - Desain UI di aplikasi android studio

*Nama: Gufranaka Samudra*
*NIM: 312110300*
*Matkul: Pemrograman Mobile*

`acttivity_main.xml`

```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TimePicker
        android:id="@+id/timePicker"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:timePickerMode="spinner"
        android:layout_gravity="center"
        android:layout_marginTop="80dp"
        android:layout_marginBottom="24dp"
        android:layout_marginLeft="20dp"
        android:layout_marginRight="20dp"/>

    <Button
        android:id="@+id/btn_time_picker"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/time_picker"
        android:layout_gravity="center"
        android:layout_marginTop="100dp"/>

</LinearLayout>
```

## Output

![output](https://raw.githubusercontent.com/AgufSamudra/PemrogramanMobile-Pert5/main/Screenshot%20(10).png)



