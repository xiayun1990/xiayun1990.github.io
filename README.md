# appLinkTest
# 通过github page 提供app的appLink功能
# 浏览器可能存在隐私保护，可在谷歌手机中的桌面浏览栏中或者火狐中选择应用打开
'
            <intent-filter android:autoVerify="true">
                <action android:name="android.intent.action.VIEW" />

                <category android:name="android.intent.category.DEFAULT" />
                <category android:name="android.intent.category.BROWSABLE" />

                <data android:scheme="https" />
                <data android:host="xiayun1990.github.io" />
                <data android:pathPattern="/tobey" />
            </intent-filter>
'
