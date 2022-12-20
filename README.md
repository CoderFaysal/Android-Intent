# Android Intent Go to Another App Activity


## Open A Application

```

setOnClickListener(new OnClickListener() {

        @Override
        public void onClick(View v) {
           
           Intent intent = new Intent(" < another application activity name with package name > ")
           startActivity(intent);
        }
    });


```

## Open B Application 

### Create a Activity  

### Go to Manifest

```

<manifest ... >
    <application ... >
        ...
        
        
        <activity
            android:name=".DetailsNews"
            android:exported="false">
            
            <meta-data
                android:name="android.app.lib_name"
                android:value="" 
                />
                
                <intent-filter>
                        <action android:name="<Secound Activity Name with Package Name>" />
                        <category android:name="android.intent.category.DEFAULT" />
                </intent-filter>
            
        </activity>
        
        
    </application>
</manifest>

```


## Better Understand - 


_© All Right Reserved by Innovative Programmer ❤️_


