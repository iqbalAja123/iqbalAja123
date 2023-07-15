<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">
    <TextView
        android:id="@+id/text_dashboard"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginStart="8dp"
        android:layout_marginTop="8dp"
        android:layout_marginEnd="8dp"
        android:textAlignment="center"
        android:textSize="20sp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <RelativeLayout
        android:layout_width="match_parent"
        android:layout_height="90sp"
        android:background="#FF008000">

        <RelativeLayout
            android:layout_width="140sp"
            android:layout_height="200sp"
            android:layout_marginTop="20dp"
            android:background="@drawable/gojek" />

        <ImageView
            android:layout_width="50sp"
            android:layout_height="50sp"
            android:layout_alignParentRight="true"
            android:layout_centerVertical="true"
            android:layout_marginTop="25sp"
            android:src="@drawable/iqbal" />

        <ImageView
            android:layout_width="50sp"
            android:layout_height="50sp"
            android:layout_marginTop="25sp"
             />
    </RelativeLayout>

    <RelativeLayout
        android:id="@+id/kel2"
        android:layout_width="370dp"
        android:layout_height="100dp"
        android:layout_centerHorizontal="true"
        android:layout_marginTop="120dp"
        >

        <RelativeLayout
            android:id="@+id/ly2"
            android:layout_width="129dp"
            android:layout_height="60dp"
            android:layout_centerVertical="true"
            android:layout_marginLeft="5dp"
            >

            <ImageView
                android:id="@+id/logo"
                android:layout_width="50dp"
                android:layout_height="50dp"

                android:layout_centerVertical="true"
                android:layout_marginLeft="10dp"
                android:src="@drawable/uang" />

            <TextView
                android:layout_width="75dp"
                android:layout_height="wrap_content"
                android:layout_centerVertical="true"
                android:layout_marginLeft="5dp"
                android:layout_toRightOf="@id/logo"
                android:text="Rp. 10.000"
                android:textColor="@color/black"
                android:textSize="12sp"
                android:textStyle="bold" />
        </RelativeLayout>


        <RelativeLayout
            android:id="@+id/ly3"
            android:layout_width="70dp"
            android:layout_height="90dp"
            android:layout_centerVertical="true"
            android:layout_marginLeft="5dp"
            android:layout_toRightOf="@id/ly2">

            <ImageView
                android:id="@+id/satu"
                android:layout_width="50dp"
                android:layout_height="50dp"
                android:layout_alignParentLeft="true"
                android:layout_centerVertical="true"
                android:layout_marginLeft="10dp"
                android:src="@drawable/saldo" />

            <TextView
                android:layout_width="70dp"
                android:layout_height="wrap_content"
                android:layout_below="@id/satu"
                android:layout_centerVertical="true"
                android:layout_marginLeft="10dp"
                android:layout_marginTop="5dp"
                android:text="Isi Saldo"
                android:textColor="@color/black"
                android:textSize="12sp"
                android:textStyle="bold" />
        </RelativeLayout>

        <RelativeLayout
            android:id="@+id/ly4"
            android:layout_width="75dp"
            android:layout_height="90dp"
            android:layout_centerVertical="true"
            android:layout_marginLeft="5dp"
            android:layout_toRightOf="@id/ly3">

            <ImageView
                android:id="@+id/tiga"
                android:layout_width="50dp"
                android:layout_height="50dp"
                android:layout_centerVertical="true"
                android:layout_marginLeft="10dp"
                android:src="@drawable/bayar" />

            <TextView
                android:layout_width="70dp"
                android:layout_height="wrap_content"
                android:layout_below="@id/tiga"
                android:layout_centerVertical="true"
                android:layout_marginLeft="18dp"
                android:layout_marginTop="5dp"
                android:text="Bayar"
                android:textColor="@color/black"
                android:textSize="12sp"
                android:textStyle="bold" />
        </RelativeLayout>

        <RelativeLayout
            android:id="@+id/ly5"
            android:layout_width="75dp"
            android:layout_height="90dp"
            android:layout_centerVertical="true"
            android:layout_marginLeft="5dp"
            android:layout_toRightOf="@id/ly4">

            <ImageView
                android:id="@+id/dua"
                android:layout_width="50dp"
                android:layout_height="50dp"
                android:layout_centerVertical="true"
                android:layout_marginLeft="10dp"
                android:src="@drawable/denda" />

            <TextView
                android:layout_width="70dp"
                android:layout_height="wrap_content"
                android:layout_below="@id/dua"
                android:layout_centerVertical="true"
                android:layout_marginLeft="18dp"
                android:layout_marginTop="5dp"
                android:text="denda"
                android:textColor="@color/black"
                android:textSize="12sp"
                android:textStyle="bold" />
        </RelativeLayout>

    </RelativeLayout>

    <RelativeLayout
        android:id="@+id/kel5"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_below="@+id/kel2"
        android:background="#ffff"
        android:layout_marginBottom="10sp"
        >

        <ImageView
            android:id="@+id/lima"
            android:layout_width="70sp"
            android:layout_height="70sp"
            android:layout_marginLeft="20dp"
            android:layout_marginTop="15sp"
            android:src="@drawable/goride" />

        <TextView
            android:layout_width="70dp"
            android:layout_height="wrap_content"
            android:layout_below="@id/lima"
            android:layout_centerVertical="true"
            android:layout_marginLeft="18dp"
            android:layout_marginTop="5dp"
            android:text="roda dua"
            android:textColor="@color/black"
            android:textSize="12sp"
            android:textStyle="bold" />

        <ImageView
            android:id="@+id/enam"
            android:layout_width="70sp"
            android:layout_height="70sp"
            android:layout_marginLeft="40dp"
            android:layout_marginTop="15sp"
            android:layout_toRightOf="@id/lima"
            android:src="@drawable/gocar" />

        <TextView
            android:layout_width="70dp"
            android:layout_height="wrap_content"
            android:layout_below="@id/lima"
            android:layout_centerVertical="true"
            android:layout_marginLeft="18dp"
            android:layout_marginTop="5dp"
            android:text="Kelompok 3"
            android:textColor="@color/black"
            android:textSize="12sp"
            android:textStyle="bold" />

        <ImageView
            android:id="@+id/tujuh"
            android:layout_width="70sp"
            android:layout_height="70sp"
            android:layout_marginLeft="40dp"
            android:layout_marginTop="15sp"
            android:layout_toRightOf="@id/enam"
            android:src="@drawable/gosend" />

        <ImageView
            android:id="@+id/delapan"
            android:layout_width="70sp"
            android:layout_height="70sp"
            android:layout_below="@+id/lima"
            android:layout_marginLeft="20dp"
            android:layout_marginTop="25sp"
            android:src="@drawable/gofood" />

        <ImageView
            android:id="@+id/sembilan"
            android:layout_width="70sp"
            android:layout_height="70sp"
            android:layout_below="@id/enam"
            android:layout_marginLeft="40dp"
            android:layout_marginTop="25sp"
            android:layout_toRightOf="@id/delapan"
            android:src="@drawable/goshop" />

        <ImageView
            android:id="@+id/sempuluh"
            android:layout_width="70sp"
            android:layout_height="70sp"
            android:layout_below="@id/tujuh"
            android:layout_marginLeft="40dp"
            android:layout_marginTop="25sp"
            android:layout_toRightOf="@id/sembilan"
            android:src="@drawable/gomaket" />

        <ImageView
            android:id="@+id/sebelas"
            android:layout_width="70sp"
            android:layout_height="70sp"
            android:layout_below="@+id/delapan"
            android:layout_marginLeft="20sp"
            android:layout_marginTop="25sp"
            android:src="@drawable/bil" />

        <ImageView
            android:id="@+id/duabelas"
            android:layout_width="70sp"
            android:layout_height="70sp"
            android:layout_below="@id/sembilan"
            android:layout_marginLeft="40dp"
            android:layout_marginTop="15sp"
            android:layout_toRightOf="@id/sebelas"
            android:src="@drawable/translit" />

        <ImageView
            android:id="@+id/tigabelas"
            android:layout_width="70sp"
            android:layout_height="70sp"
            android:layout_below="@id/sempuluh"
            android:layout_marginLeft="40dp"
            android:layout_marginTop="25sp"
            android:layout_toRightOf="@id/duabelas"
            android:src="@drawable/club" />
    </RelativeLayout>

    <HorizontalScrollView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:layout_below="@id/kel5"
        android:layout_centerHorizontal="true"
        android:layout_centerVertical="true"
        >

        <LinearLayout
            android:id="@+id/lyuscrol"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:orientation="horizontal">

            <ImageView
                android:id="@+id/sc1"
                android:layout_width="400sp"
                android:layout_height="350sp"
                android:layout_marginLeft="10sp"

                android:src="@drawable/vocher" />

            <ImageView
                android:id="@+id/sc2"
                android:layout_width="400sp"
                android:layout_height="350sp"
                android:layout_marginLeft="10dp"
                android:layout_marginTop="1sp"
                android:src="@drawable/promo" />

            <ImageView
                android:id="@+id/sc3"
                android:layout_width="400sp"
                android:layout_height="350sp"
                android:layout_marginLeft="10dp"
                android:layout_marginTop="1sp"
                android:src="@drawable/pintar" />

            <ImageView
                android:id="@+id/sc4"
                android:layout_width="400sp"
                android:layout_height="380sp"
                android:layout_marginLeft="10dp"
                android:layout_marginTop="1sp"
                android:src="@drawable/pakai" />
        </LinearLayout>
    </HorizontalScrollView>


</RelativeLayout>
