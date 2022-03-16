# PB

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:background="@color/backgraund">

<LinearLayout android:id="@+id/LL1"
android:layout_width="match_parent"
android:layout_height="match_parent"
android:orientation="vertical"
android:gravity="center_horizontal"
app:layout_constraintStart_toStartOf="parent"
app:layout_constraintTop_toTopOf="parent">

 <ImageView
     android:layout_width="match_parent"
     android:layout_height="320dp"
     android:src="@drawable/ss"
     android:layout_marginTop="20dp"/>


    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:gravity="center_vertical"
        android:orientation="horizontal"
        android:layout_marginTop="30dp"
        android:layout_marginLeft="10dp"
        android:layout_marginRight="10dp"
        >

        <Button
            android:id="@+id/female"
            android:layout_width="180dp"
            android:layout_height="340dp"
            android:backgroundTint="@color/f"
            android:text="female"
            android:textColor="@color/D"
            android:textSize="23sp"

            />

        <LinearLayout
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"

>
            <Button
                android:id="@+id/male"
                android:layout_width="180dp"
                android:layout_height="340dp"

                android:layout_marginLeft="15dp"
                android:layout_marginRight="10dp"
                android:backgroundTint="@color/f"
                android:text="male"
                android:textColor="@color/C"
                android:textSize="23sp"

                />







        </LinearLayout>
    </LinearLayout>

    </LinearLayout>
</androidx.constraintlayout.widget.ConstraintLayout>
