# PageLogin @2

      <?xml version="1.0" encoding="utf-8"?>
      <RelativeLayout
          xmlns:android="http://schemas.android.com/apk/res/android"
          xmlns:app="http://schemas.android.com/apk/res-auto"
          xmlns:tools="http://schemas.android.com/tools"
          android:layout_width="match_parent"
          android:layout_height="match_parent"
          tools:context=".MainActivity">

          <ImageView
              android:layout_width="50dp"
              android:layout_height="40dp"
              android:layout_marginLeft="10dp"
              android:layout_marginTop="20dp"
              android:src="@drawable/backButton"

          <ImageView
              android:layout_width="125dp"
              android:layout_height="120dp"
              android:layout_marginLeft="280dp"
              android:src="@drawable/logo1"

          <TextView
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:layout_marginTop="140dp"
              android:layout_marginLeft="50dp"
              android:textSize="70dp"
              android:textStyle="bold"
              android:textColor="@color/black"
              android:text="Hi !"

          <TextView
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:layout_marginTop="195dp"
              android:layout_marginLeft="50dp"
              android:textSize="70dp"
              android:textStyle="bold"
              android:textColor="@color/black"
              android:text="Welcome"

          <TextView
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:layout_marginTop="270dp"
              android:layout_marginLeft="55dp"
              android:textSize="15dp"
              android:textColor="@color/cardview_dark_background"
              android:text="I'm waiting for you, please enter your detail"

          <EditText
              android:id="@+id/user"
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:layout_marginTop="360dp"
              android:layout_marginLeft="55dp"
              android:layout_marginRight="70dp"
              android:textSize="15dp"
              android:textColor="@color/cardview_shadow_start_color"
              android:hint="Username, Email or Phone Number"

          <com.google.android.material.textfield.TextInputLayout
              app:passwordToggleEnabled="true"
              android:id="@+id/showPass"
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:layout_marginTop="400dp"
              android:layout_marginLeft="55dp"
              android:layout_marginRight="70dp"
              android:textColor="@color/cardview_shadow_start_color"

          <EditText
              android:id="@+id/password"
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:layout_marginTop="410dp"
              android:layout_marginLeft="55dp"
              android:layout_marginRight="70dp"
              android:textSize="15dp"
              android:textColor="@color/cardview_shadow_start_color"
              android:maxLength="8"
              android:hint="Password"

          <CheckBox
              android:id="@+id/rememberMe"
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:layout_marginRight="275dp"
              android:layout_marginTop="450dp"

          <TextView
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:layout_marginTop="463dp"
              android:layout_marginLeft="80dp"
              android:textSize="15dp"
              android:text="Remember Me"

          <EditText
              android:id="@+id/forgotPassword"
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:layout_marginTop="463dp"
              android:layout_marginLeft="215dp"
              android:textSize="15dp"
              android:background="@android:color/transparent"
              android:text="Forgot Password ?"



          <Button
              android:id="@+id/loginButton"
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:onClick="clickLogin"
              android:layout_marginLeft="60dp"
              android:layout_marginRight="60dp"
              android:layout_marginTop="500dp"
              android:background="@android:color/black"
              android:text="Log In" />

          <TextView
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:layout_marginTop="670dp"
              android:layout_marginLeft="90dp"
              android:textSize="15dp"
              android:text="Don't have an account ?"

          <EditText
              android:id="@+id/signUp"
              android:layout_width="match_parent"
              android:layout_height="wrap_content"
              android:layout_marginTop="670dp"
              android:layout_marginLeft="251dp"
              android:textSize="15dp"
              android:background="@android:color/transparent"
              android:text="Sign Up"


      </RelativeLayout>

