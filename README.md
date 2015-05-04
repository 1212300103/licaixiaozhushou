# licaixiaozhushou
是一款理财的软件，可以进行类别维护，收入和支出的随时记录，还有计算器的功能，可以查询支出和收入，可以进行个人信息完善
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical"
    android:background="#BEBEBE"
    android:layout_width="fill_parent"
    android:layout_height="fill_parent">
	    
	    <LinearLayout
	        android:layout_width="fill_parent"
	        android:layout_height="wrap_content"
	        android:layout_marginBottom="4dip"
	        android:layout_marginLeft="15dip"
	        android:layout_marginRight="15dip"
	        android:layout_marginTop="4dip"
	        android:background="@drawable/navigator"
	        android:gravity="center"
	        android:orientation="horizontal" >

	        <TextView
	            android:layout_width="100dip"
	            android:layout_height="wrap_content"
	            android:layout_marginRight="10dip"
	            android:gravity="center"
	            android:text="菜单"
	            android:textColor="#000000"
	            android:textSize="18dip"
	            android:textStyle="bold" >
	        </TextView>

	        <TextView
	            android:layout_width="100dip"
	            android:layout_height="wrap_content"
	            android:layout_marginLeft="10dip"
	            android:layout_weight="0.20"
	            android:background="@drawable/hilight"
	            android:gravity="center"
	            android:text="理财维护"
	            android:textColor="#000000"
	            android:textSize="20dip"
	            android:textStyle="bold" >
	        </TextView>
	    </LinearLayout>

	<RadioGroup android:id="@+id/RadioGroup01"
	    android:orientation="horizontal" 
	    android:background="#B0C4DE"
	    android:layout_marginTop="1dip"
	    android:gravity="center"
		android:layout_width="fill_parent"
		android:layout_height="wrap_content">
		<RadioButton android:id="@+id/RadioButton01"
			android:text="收入维护" 
			android:layout_marginLeft="3dip"
			android:checked="true"
			android:layout_width="wrap_content"
			android:layout_height="wrap_content">
		</RadioButton>
		<RadioButton android:id="@+id/RadioButton02"
			android:text="支出维护"
			android:layout_marginLeft="20dip"
			android:layout_width="wrap_content"
			android:layout_height="wrap_content">
		</RadioButton>
	</RadioGroup>
	<ListView android:id="@+id/ListView01" 
		android:layout_width="fill_parent"
		android:layout_height="235dip">
	</ListView>	
	<LinearLayout android:id="@+id/LinearLayout01" 
		android:background="#B0C4DE"
	    android:gravity="center"
		android:layout_width="fill_parent"
		android:layout_height="wrap_content">
		<TextView android:id="@+id/TextView02" 
			android:text="类别添加:" 
			android:textColor="#FFFFFF"
			android:layout_marginLeft="2dip"
			android:textSize="16dip"
			android:layout_width="wrap_content" 
			android:layout_height="wrap_content">
		</TextView>
		<EditText android:id="@+id/EditText01" 
			android:layout_marginTop="3dip"
			android:layout_marginLeft="5dip"
			android:layout_width="160dip" 
			android:layout_height="40dip">
		</EditText>
	</LinearLayout>
	
	<LinearLayout android:id="@+id/LinearLayout02" 
		android:background="#B0C4DE"
	    android:gravity="center"
		android:layout_width="fill_parent"
		android:layout_height="wrap_content">
		<TextView android:id="@+id/TextView02" 
			android:text="类别说明:" 
			android:textColor="#FFFFFF"
			android:layout_marginLeft="2dip"
			android:textSize="16dip"
			android:layout_width="wrap_content" 
			android:layout_height="wrap_content">
		</TextView>
		<EditText android:id="@+id/EditText02" 
			android:layout_marginTop="1dip"
			android:layout_marginLeft="5dip"
			android:layout_width="160dip" 
			android:layout_height="40dip">
		</EditText>
	</LinearLayout>
	
	<LinearLayout android:id="@+id/LinearLayout02" 
		android:orientation="horizontal"
	    android:background="#B0C4DE"
		android:layout_width="fill_parent"
		android:layout_height="wrap_content">
		<Button android:text="添加" 
			android:id="@+id/Button01" 
			android:textSize="16dip"
			android:layout_marginLeft="10dip"
			android:layout_width="80dip" 
			android:layout_height="40dip">
		</Button>
		<Button android:id="@+id/Button02" 
			android:text="删除" 
			android:textSize="16dip"
			android:layout_marginLeft="34dip"
			android:layout_width="80dip" 
			android:layout_height="40dip">
		</Button>
		<Button android:id="@+id/Button03" 
			android:text="返回" 
			android:textSize="16dip"
			android:layout_marginLeft="32dip"
			android:layout_width="80dip" 
			android:layout_height="40dip">
		</Button>
	</LinearLayout>
</LinearLayout>
