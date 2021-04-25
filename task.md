## Main.xml file

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:orientation="vertical"
    android:layout_margin="10dp"
    tools:context=".MainActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <ImageView
            android:layout_width="30dp"
            android:layout_height="30dp"
            android:src="@drawable/ic_baseline_share_24"/>
        <TextView
            android:layout_marginTop="10dp"
            android:text="  @string/share"
            android:textSize="15sp"
            android:textColor="#000"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            />
    </LinearLayout>

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:textSize="15sp"
        android:layout_margin="10dp"
        android:fontFamily="sans-serif"
        android:text=" Share about your alumni network on\n social media and help grow the  network."
        />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginTop="5dp"
        android:gravity="center"
        android:orientation="horizontal">

        <ImageView
            android:id="@+id/facebook"
            android:layout_width="40dp"
            android:layout_height="40dp"
            android:layout_gravity="center"
            android:layout_marginTop="10dp"
            android:src="@drawable/facebook"
            android:layout_margin="5dp"
            android:scaleType="fitXY"/>
        <ImageView
            android:id="@+id/linkedin"
            android:layout_width="40dp"
            android:layout_height="40dp"
            android:layout_gravity="center"
            android:layout_margin="5dp"
            android:layout_marginTop="10dp"
            android:src="@drawable/li"
            android:scaleType="fitXY"/>

        <ImageView
            android:id="@+id/twit"
            android:layout_width="40dp"
            android:layout_height="40dp"
            android:layout_gravity="center"
            android:layout_marginTop="10dp"
            android:layout_margin="5dp"
            android:src="@drawable/tw"
            android:scaleType="fitXY"/>


        <ImageView
            android:id="@+id/icon"
            android:layout_width="40dp"
            android:layout_height="40dp"
            android:layout_margin="5dp"
            android:layout_gravity="center"
            android:layout_marginTop="10dp"
            android:src="@drawable/wh"
            android:scaleType="fitXY"/>


    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="60dp"
        android:background="@drawable/shape"
        android:layout_margin="5dp"
        android:layout_marginTop="10dp"
        android:orientation="horizontal">
        <ImageView
            android:layout_width="20dp"
            android:layout_height="20dp"
            android:layout_margin="1dp"
            android:src="@drawable/ic_baseline_share_24"/>
        <TextView
            android:text="Event Tickets "
            android:textSize="15sp"
            android:layout_margin="2dp"
            android:textColor="#000"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginLeft="135dp"
            android:text="View"
            android:textColor="#009688"
            android:textSize="15sp" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="60dp"
        android:background="@drawable/shape"
        android:layout_margin="2dp"
        android:layout_marginTop="10dp"
        android:orientation="horizontal">
        <ImageView
            android:layout_width="20dp"
            android:layout_height="20dp"
            android:layout_margin="2dp"
            android:src="@drawable/ic_baseline_share_24"/>
        <TextView
            android:text="Membership Card "
            android:textSize="15sp"
            android:textColor="#000"
            android:layout_margin="1dp"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginLeft="110dp"
            android:text="View"
            android:textColor="#009688"
            android:textSize="15sp" />

    </LinearLayout>



    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical"
        >
        <androidx.cardview.widget.CardView
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@drawable/shape"
            app:cardCornerRadius="10dp"
            app:cardElevation="5dp"
            app:cardUseCompatPadding="true"
            >

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="vertical"
                >

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:orientation="horizontal">

                    <ImageView
                        android:layout_width="30dp"
                        android:layout_height="30dp"
                        android:layout_margin="18dp"
                        android:src="@drawable/ic_baseline_account_box_24" />

                    <TextView
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_marginTop="22dp"
                        android:text="   My Profile"
                        android:textColor="#000"
                        android:textSize="15sp" />

                </LinearLayout>


                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginTop="1dp"
                    android:orientation="horizontal">
                    <ImageView
                        android:layout_width="50dp"
                        android:layout_height="50dp"
                        android:layout_margin="5dp"
                        android:src="@drawable/ic_baseline_account_circle_24" />

                    <LinearLayout
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_marginTop="1dp"
                        android:orientation="vertical">
                        <TextView
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:layout_margin="5dp"
                            android:text="Bommini SivaPrasad"
                            android:src="@drawable/wh" />
                        <TextView
                            android:layout_width="wrap_content"
                            android:layout_height="wrap_content"
                            android:text="@string/view"
                            android:autoLink="all"
                            android:layout_margin="2dp"
                            android:src="@drawable/wh" />
                    </LinearLayout>

                </LinearLayout>

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:orientation="horizontal"
                    >
                    <Button
                        android:layout_width="165dp"
                        android:layout_height="35dp"
                        android:layout_margin="2dp"
                        android:text="Add Work Details"
                        android:background="@drawable/gshape"
                        android:textAllCaps="false"/>
                    <Button
                        android:layout_width="155dp"
                        android:background="@drawable/yshape"
                        android:layout_height="35dp"
                        android:backgroundTint="@color/yelow"
                        android:text="Update Location"
                        android:textAllCaps="false"/>

                </LinearLayout>

                <Button
                    android:layout_gravity="center"
                    android:layout_width="165dp"
                    android:layout_height="35dp"
                    android:text="Update Picture"
                    android:background="@drawable/bshape"
                    android:backgroundTint="@color/blue"
                    android:layout_margin="6dp"
                    android:textAllCaps="false"/>

            </LinearLayout>


        </androidx.cardview.widget.CardView>



    </LinearLayout>
</LinearLayout>

# blue.xml file

```
<?xml version="1.0" encoding="utf-8"?>
<selector xmlns:android="http://schemas.android.com/apk/res/android">
    <item android:state_pressed="false">
        <shape android:shape="rectangle">
            <corners android:radius="1000dp" />
            <solid android:color="#03A9F4" />
            <padding
                android:bottom="4dp"
                android:left="4dp"
                android:right="4dp"
                android:top="4dp" />
        </shape>
    </item>
    <item android:state_pressed="true">
        <shape android:shape="rectangle">
            <corners android:radius="1000dp" />
            <solid android:color="#2196F3" />
            <stroke
                android:width="2dip"
                android:color="#2196F3" />
            <padding
                android:bottom="4dp"
                android:left="4dp"
                android:right="4dp"
                android:top="4dp" />
        </shape>
    </item>

</selector>

```
# yelow.xml file

```
<?xml version="1.0" encoding="utf-8"?>
<selector xmlns:android="http://schemas.android.com/apk/res/android">
    <item android:state_pressed="false">
        <shape android:shape="rectangle">
            <corners android:radius="1000dp" />
            <solid android:color="#FFC107" />
            <padding
                android:bottom="4dp"
                android:left="4dp"
                android:right="4dp"
                android:top="4dp" />
        </shape>
    </item>
    <item android:state_pressed="true">
        <shape android:shape="rectangle">
            <corners android:radius="1000dp" />
            <solid android:color="#FFC107" />
            <stroke
                android:width="2dip"
                android:color="#FFC107" />
            <padding
                android:bottom="4dp"
                android:left="4dp"
                android:right="4dp"
                android:top="4dp" />
        </shape>
    </item>

</selector>

```

# green.xml file

```
<?xml version="1.0" encoding="utf-8"?>
<selector xmlns:android="http://schemas.android.com/apk/res/android">
    <item android:state_pressed="false">
        <shape android:shape="rectangle">
            <corners android:radius="1000dp" />
            <solid android:color="#4CAF50" />
            <padding
                android:bottom="4dp"
                android:left="4dp"
                android:right="4dp"
                android:top="4dp" />
        </shape>
    </item>
    <item android:state_pressed="true">
        <shape android:shape="rectangle">
            <corners android:radius="1000dp" />
            <solid android:color="#4CAF50" />
            <stroke
                android:width="2dip"
                android:color="#4CAF50" />
            <padding
                android:bottom="4dp"
                android:left="4dp"
                android:right="4dp"
                android:top="4dp" />
        </shape>
    </item>

</selector>
```
