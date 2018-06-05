# Maven
项目组件远程仓库


    
    视频组件：
    repositories {
         maven { url "https://raw.githubusercontent.com/zfl5232577/maven/master" }
    }
   
    dependencies {
        implementation "com.mark:BaseChatForAndroid:1.0.0"
    }
    
    AOP切面框架：
    buildscript {
        repositories {
            maven { url "https://raw.githubusercontent.com/zfl5232577/maven/master" }
        }
        dependencies {
            classpath 'com.mark:markaop-plugin:1.0.0'
        }
    }
    
    app的build.gradle文件
    apply plugin: 'com.android.application'
    apply plugin: 'markaop-plugin'
     
