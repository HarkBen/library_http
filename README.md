# 基础库 [![](https://www.jitpack.io/v/HarkBen/library_http.svg)](https://www.jitpack.io/#HarkBen/library_http)

# tb_rxretrofit 网络请求

1.项目根目录 build.gradle 添加
```
allprojects {
		repositories {
			...
			maven { url 'https://www.jitpack.io' }
		}
	}
```

2.module目录 build.gradle 添加

```
implementation 'com.github.HarkBen:library_http:0.9'
```

混淆

```
-dontwarn okhttp3.logging.**
-keep class okhttp3.internal.**{*;}
-dontwarn okio.**
```

