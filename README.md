### How to be an android developer Expert
In this Post  I am going to talk about the steps you should follow to be an  android developer expert  in the market. At the beginning, I would like to say something about that. The corner stone of success in any field is to love what you do so if you do not have passion to learn android development you will waste your time.It is  a long journey of learning and practice.To be expert , there are many steps you should follow. Here are the steps:



Mastering Java Programming and Kotlin
Mastering Design Patterns
Mastering Data Structures and Algorithms
Mastering Android development SDK
Mastering the trending tools and libraries
Mastering the Clean Architecture by Uncle Bob
Version Control and Continuous Integration Tools
Having Problem Solving Skill
Having Self Learning Skill
Having Github,StackOverflow Accounts
Now let us talk more about each point  form my point of view to be an android developer expert:

Java is an amazing,easy,portable language  used to develop android native applications.There are three versions of Java(J2SE,J2EE,J2ME).For android development we use J2SE(Java Standard Edition). You should learn it very well.The more you practice in Java,The more you will be android ninja.the following are some resources for learning

Oracle Documentation Siteandroid developer Expert
Effective Java Book
Kotlin is the new supported language for android developement.It is easy,powerful and has more powerful features than Java Language.If you learn it, you will be happy with nice and easy coding and you can code  both  in Java and kotlin in the same project.Consequently, it is fun.The following are some resources for Kotlin Learning:

Kotlin Documnetation
Kotlin For Android Developers book
Kotlin in Action Book
Design patterns are group of solutions for common problems.They developed by Group of Pioneers in Software Engineering Field. Design Patterns have three categories i.e,Creational ,Structural and Behavioral Patterns.You should first understand the problem before  trying to use the pattern for writing better and efficient code.The following  are some resources for learning design patterns:

Head First Design Patterns Book
DoFactoryWebsite
Data Structures and algorithms are the corner stones of your life as a software engineer.We develop apps for mobile platform. We have limited resources of memory and processors .So we want efficient ways to store data in small size of memory. We always want our program to run fast with any size of inputs and here data structures and  algorithms techniques appear on the scene .

To be an android developer expert , you should be professional in data structures and algorithms techniques.The following are some resources to master data structures and algorithms:

DataStructures and Algorithms in Java book
Introduction to Algorithms Book
Android OS(operating system) is a great open source operating system designed on the top of Linux Kernel .It is working on Smart Devices Like smart phones, watches,TVs and many embedded devices.you should install latest version of Android Studio and get started  to work with android Software development kit.

You should study the basics very well to be able to build awesome apps .The following are some resources to master android SDK:

Android Developers WebSite
The Big Nerd Ranch Book
Introduction to android development Book
 Trending Tools And Libraries: There are some useful libraries that accelerate your development as android developer expert and save a lot of time like:

Retrofit
GSON
RxJava
Dagger2
Glide
EventBus
Parceler
Architecture Components
Roboelectric
Espersso
More  .
Clean architecture is one of the best architectures for software development in general and for android apps specific also.This architecture divides your app into three separated layers  as following:

Presentation Layer: this layer is responsible for UI and you can use MVP or MVVM with Data binding
Domain Layer: this layer is responsible for business only
Data Layer: this layer is responsible for data from different sources like database,network and files
You should be familiar with Version Control Tools like Git  to manage your code history and collaborate with your team and Continuous integration tools  like Jenkins and Travis to make sure you don't break the team commit and push formats and do not break the code base of your team.

Problem solving is an essential skill for any  programmer because the programming language is  a tool of writing the solution of a problem only  but the solution lies in logical thinking .The more you train your mind to solve problems ,The more you will be a better software engineer.

For Software Domain I think the websites like the following are a great place to solve great problems and enhance your problem solving skills:

HackerRank
CodeWars
Codility.   
Self Learning is a vital Skill for your career as software engineer. There is no end of knowledge and science and every day there is new technology comes to life.So to be able to update your self with the new stuff ,you should learn every day and read more .Do not wait someone to teach you something. Be proactive and learn by your self .

Github and Stackoverflow are famous websites for code repository hosting and for asking and answering questions .As a software engineer, you should have account on GitHub.You can  share and contribute in open source projects.This makes you a better developer and also famous  in your community.

At the end, I would like to say that all the previous points are of  my point of view to be an android developer expert  in the market.I hope this article will help you to start your journey of android   development.


###How to Speed Up Your Android Gradle Build
In this post I am going to talk about Gradle build time issue when you develop your android app.If you work on  a large app with huge number of resources ,many classes and a lot of third part libraries. You will face this issue.

So, in this post I will share some tips to resolve this issue and save your precious time .To be able to focus on developing of your app.In the beginning let us know the impact of this issue on our productivity as android developers. Suppose you work in large project for example chat app. And you build your project 50 times per day .Let us assume  the Gradle build time takes around 2 minutes so the total time is 100  minutes(1 hour and 40 min) .This is a huge waste time so I think that you should give this post some times .

To understand and apply to your next projects.Before talking about the tips you should understand the building process of Gradle and here are the building process steps:

Initialization:In this stage of the Gradle build life cycle, Gradle picks the project and decides what things to build.
Configuration: Gradle will evaluate your build.gradle script, configure all the plugins and evaluate the task graph.
Execution: In this phase Gradle actually runs all the task those were evaluated in previous phase to get the work done and build the application.
Now Put the following in gradle.properties file in your project to reduce the build time



Awesome!!! is not it? let us talk more about each attribute in the gradle.properties file and how it helps us to reduce the build time .Are you ready ? here are the attributes:

Gradle Daemon: Gradle has a nice feature called Daemon. Daemon keeps instance of gradle up and running  in background for the next builds and this will remove the amount of time required for gradle initialization every build.
Heap Size:The more you give heap size for Daemon ,The more you will reduce the build time.
Parallel Mode: This options will help you if you organize your app in modules not all in one module(app module)
ConfigureOnDemand: This tells gradle to build the required modules only
Finally I hope this video will give you more tips to reduce your Gradle build time and enhance your productivity. Please comment and share your experience in this issue with me


###How to build chat application like whatsapp

In this post I am going to talk about how to build a chat application like WhatsApp. No one can deny that chatting apps  are a great methods for real time communication. There are easy,fast and cheap way to communicate with each other. At the beginning let us analyze WhatsApp . This application has three core features as the following:



Chatting: One to one chatting and Group Chatting
Calling:  Audio and Video Calling
Secured Communication: Encrypted messages and  calling 
Nice ,how can I build these features from scratch?

OK. let me share my experience with you. It was a great chance for me to work with amazing team to build a chat application  like WhatsApp and we did it, so I  will share  the technologies we used . We build a chat application based on XMPP . XMPP(Extensible messaging and presence protocol) is a great protocol for handling messaging and presence for users.XMPP has core features and additional features called extensions  and this is overview about XMPP features :

XMPP Overview
Amazing Introduction to XMPP
To exchange the messages between two end points through XMPP server you need to follow the protocol from your client side (Android/IOS).We usedSmack Library as our XMPP client and we Used OpenFire Server  as our back end server with external MySQL database . You should  use the open source code of smack  and use it as project in your  build.gradle file and also for your open fire you want to build it  because you will often modify it according to your business. we modified them to suite our needs.The following are some resources to learn Smack library:

Smack Documentaion
ِAndroid chat Demo based on Smack
To be able to make real time video and audio calling or screen sharing also ,you should use WebRTC Technology . WebRTC enables you to make real time communication through two steps

Signaling: firstly, you should do some signaling between the caller and the callee to exchange your media info and bit rate and more . Also You send offer to the callee then callee sends  answer if he wants to answer you .Before that you must be connected to some room on AppRTC Server .You should build your own AppRTC server with your TURN and STUN servers.
Peer-to- Peer communication:  here you call your end point using peer to peer technology and there is no server in the middle.
The following are some useful resources to learn more about WebRTC:

WebRTC Tutorials on Medium Website 
Android webrtc Client based on Socket.io
Now ,we will talk about the hardest part ,in my point of view encryption is the most challenge task for building chat app and this because is not easy task especially if you do not study encryption course before ,so  I will talk about the more secure and advanced protocol for encryption until now. Signal protocol is one of the highest encryption protocol nowadays.Signal is build by

Whisper Systems company . It is secure and open source ,also it is used by the biggest companies in the world like Google,Facebook and WhatsApp. Unfortunately there is no samples for its implementation on Github so I will share the following only :

Libsignal-Protocol Lib
Facebook and whatsapp papers
Finally ,I hope this article will helps you to build your own chat application. Please share your experience with me through commenting on this post if you have experience with chatting apps



###How To Reduce  APK size for Google Play Store

In this post I am going to talk about how to reduce Apk size  for application publishing on Google play.There is no  doubt that APK size  is very important from user perspective. Because many people have limited memory for apps .They also have poor internet  connection in many countries around the world especially the developing countries. So, you must put the size of your app in your consideration and do your best to reduce Apk size.

Now, I will share with you some tips to help you to reduce Apk size.There are many factors which reduce the Application size and these are the most effective ones:

Proguard
resources shrinking
vector drawable
downloadable fonts
Proguard minimizes the application size by recurring method names,field names and class names and replace them with small names (obsfuscation).It removes unused code also so it is harder for anyone who want to decompile your app to get the source code.This is common configuration for libraries.Gradle will handle this through the following:

android {
  buildTypes {
    release {
      minifyEnabled true
    }
  }
}
Proguard gets its configuration from file called proguard-rules.pro in your app root folder.If you try to use proguard  in your folder you may get warnings for used libraries and to solve this issue put

——    dontwarn package of the library .**
in proguard-rules.pro .

For example like this for RxJava

-dontwarn rx.**

If you want to prevent obfuscating  for some class do the following:

-keep class com.ramadan.BaseActivity**

here you prevent obfuscation for class called BaseActivity.

Resource shrinking  removes the unused resources  form your app.Gradle will helps you too in this option like the following

android {
    // Other settings

    buildTypes {
        release {
            minifyEnabled true
            shrinkResources true
            proguardFiles getDefaultProguardFile('proguard-android.txt'), 'proguard-rules.pro'
        }
    }
}
vector drawables is a mother way  instead of  different folders of different resolutions.This is really very helpful but it has more cpu load so you should think in this option carefully.Drawable font is a new technique where all apps will use their fonts from common provider .

Finally , This is useful video to help you to learn more tips about application reduction.If you have any more tips please share it with me

###Animation
In this post I am going to talk about animation framework for Android.Android supports powerful animation for both views and transition between activities.The most important one is Property Animation.There are three type of animation for android

View Animation
Property Animation
Transition Animation
In this tutorial I will take about the View Animation.The View Animation system is the simplest of the three mechanisms. The primary method of creating animations prior to Android 3.0 was the view animation system. View animation provides a series of built-in animation operations that generate in-between, or tween, views. You supply the starting and ending values, and the animation framework will transform the displayed view. This system is simple to implement, but it has a few drawbacks. First, it’s limited to operating on View objects. If you want to animate something that is not a view, you’ll need to do so yourself. Second, it operates only on a default set of properties; it does not affect other properties.

Finally, view animation alters only how the view is drawn, not where it is positioned. Importantly, the rectangular hit area of views is not moved during a view animation—a common bug found in animation code. You need to alter the view after the animation is finished to update its position.

These limitations led to the deprecation of the view animation framework in Android 3.0 and later. However, there are still a large number of pre-3.0 devices in use, so when possible you should use the view animation framework for maximum app compatibility.

Defining Animations
Like most UI code in Android, animations can be defined either in code or in XML. It’s preferred to use XML, however, because it is easier to create complex animations and is easily reusable. View animations defined in XML are placed in the res/anim/ folder. The basic structure of an animation is similar to that of a view. These are the available options for view animation:

scale, which changes the view size
translate, which moves the view
rotate, which rotates view
alpha, which changes the transparency of a view
Now we will start the first example :Simple Scale animation Tutorial for Android

The output like the following screen where there are two image views  when user click on each of them third image view with scale animation will appears.



let us define the scene first for our animation (activity_main.xml) like the following:

<?xml version="1.0" encoding="utf-8"?>
<FrameLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent" >

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        >


        <LinearLayout
            android:id="@+id/layout"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:gravity="center_horizontal"
            android:orientation="horizontal" >

            <ImageView
                android:id="@+id/imageView1"
                android:layout_width="0dp"
                android:layout_height="150dp"
                android:layout_weight="1.0"
                android:padding="10dp"
                android:clickable="true"
                android:onClick="imageClicked"
                android:src="@drawable/prymids" />

            <ImageView
                android:id="@+id/imageView2"
                android:layout_width="0dp"
                android:layout_height="150dp"
                android:layout_weight="1.0"
                android:padding="10dp"
                android:clickable="true"
                android:onClick="imageClicked"
                android:src="@drawable/effel" />

        </LinearLayout>

        <ImageView
            android:id="@+id/animatedImage"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:visibility="gone" />


    </LinearLayout>


</FrameLayout

Now, Let us define our activity called (MainActivity.java)
package com.ramadan_apps.androidanimation;

import android.os.Bundle;
import android.support.v7.app.AppCompatActivity;
import android.view.View;
import android.view.animation.Animation;
import android.view.animation.AnimationUtils;
import android.widget.ImageView;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

    }

    public void imageClicked(View thumbnailView) {
        ImageView thumbnail = (ImageView)thumbnailView;
        ImageView animatedImage = (ImageView) findViewById(R.id.animatedImage);

        animatedImage.setImageDrawable(thumbnail.getDrawable());
        animatedImage.setVisibility(View.VISIBLE);

        Animation animation
                = AnimationUtils.loadAnimation(this, R.anim.scale_animation01);
        animatedImage.startAnimation(animation);
    }
}

In this post I am going to talk about animation framework for Android.Android supports powerful animation for both views and transition between activities.The most important one is Property Animation.There are three type of animation for android

View Animation
Property Animation
Transition Animation
In this tutorial I will take about the View Animation.The View Animation system is the simplest of the three mechanisms. The primary method of creating animations prior to Android 3.0 was the view animation system. View animation provides a series of built-in animation operations that generate in-between, or tween, views. You supply the starting and ending values, and the animation framework will transform the displayed view. This system is simple to implement, but it has a few drawbacks. First, it’s limited to operating on View objects. If you want to animate something that is not a view, you’ll need to do so yourself. Second, it operates only on a default set of properties; it does not affect other properties.

Finally, view animation alters only how the view is drawn, not where it is positioned. Importantly, the rectangular hit area of views is not moved during a view animation—a common bug found in animation code. You need to alter the view after the animation is finished to update its position.

These limitations led to the deprecation of the view animation framework in Android 3.0 and later. However, there are still a large number of pre-3.0 devices in use, so when possible you should use the view animation framework for maximum app compatibility.

Defining Animations
Like most UI code in Android, animations can be defined either in code or in XML. It’s preferred to use XML, however, because it is easier to create complex animations and is easily reusable. View animations defined in XML are placed in the res/anim/ folder. The basic structure of an animation is similar to that of a view. These are the available options for view animation:

scale, which changes the view size
translate, which moves the view
rotate, which rotates view
alpha, which changes the transparency of a view
Now we will start the first example :Simple Scale animation Tutorial for Android

The output like the following screen where there are two image views  when user click on each of them third image view with scale animation will appears.



let us define the scene first for our animation (activity_main.xml) like the following:

<?xml version="1.0" encoding="utf-8"?>
<FrameLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent" >

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        >


        <LinearLayout
            android:id="@+id/layout"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:gravity="center_horizontal"
            android:orientation="horizontal" >

            <ImageView
                android:id="@+id/imageView1"
                android:layout_width="0dp"
                android:layout_height="150dp"
                android:layout_weight="1.0"
                android:padding="10dp"
                android:clickable="true"
                android:onClick="imageClicked"
                android:src="@drawable/prymids" />

            <ImageView
                android:id="@+id/imageView2"
                android:layout_width="0dp"
                android:layout_height="150dp"
                android:layout_weight="1.0"
                android:padding="10dp"
                android:clickable="true"
                android:onClick="imageClicked"
                android:src="@drawable/effel" />

        </LinearLayout>

        <ImageView
            android:id="@+id/animatedImage"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:visibility="gone" />


    </LinearLayout>


</FrameLayout

Now, Let us define our activity called (MainActivity.java)
package com.ramadan_apps.androidanimation;

import android.os.Bundle;
import android.support.v7.app.AppCompatActivity;
import android.view.View;
import android.view.animation.Animation;
import android.view.animation.AnimationUtils;
import android.widget.ImageView;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

    }

    public void imageClicked(View thumbnailView) {
        ImageView thumbnail = (ImageView)thumbnailView;
        ImageView animatedImage = (ImageView) findViewById(R.id.animatedImage);

        animatedImage.setImageDrawable(thumbnail.getDrawable());
        animatedImage.setVisibility(View.VISIBLE);

        Animation animation
                = AnimationUtils.loadAnimation(this, R.anim.scale_animation01);
        animatedImage.startAnimation(animation);
    }
}

<?xml version="1.0" encoding="utf-8"?>

<set xmlns:android="http://schemas.android.com/apk/res/android" >

    <scale
        android:duration="300"
        android:fromXScale="0.0"
        android:fromYScale="0.0"
        android:toXScale="1.0"
        android:toYScale="1.0" />

</set>


 To download the full project please visit my repository on Github
 In this post I am going to continue the talk about android animation ,specially The Property Animation.  I f you did not know any thing about animation in android please read the

 Part1.
In The previous Part1 we talked about view animation and we knew that we can animate any view using view animation.Unfortunately, we can not animate any property inside this view so the property animation appears on the scene.

Android 3.0 introduced property animation to enable object animation not only view s.This can be  done by using one of these classes:

ObjectAnimator
Value Animator
Time Animator
Animator Set
Let us see the next example.this is Rotation animation around y-axis for image view using object animator .

the output is screen with image view which is clickable and it start rotating around y- axis  after user click it like the following:



Firstly define your animation in res/animator/flip_on_vertical.xml

<?xml version="1.0" encoding="utf-8"?>
<objectAnimator xmlns:android="http://schemas.android.com/apk/res/android"
    android:duration="500"
    android:valueFrom="0"
    android:valueTo="360"
    android:propertyName="rotationY"
    android:valueType="floatType"
    >

</objectAnimator>

and we define the scene of animation  like this:
package com.ramadan_apps.androidanimation;

import android.animation.Animator;
import android.animation.AnimatorInflater;
import android.os.Bundle;
import android.support.v7.app.AppCompatActivity;
import android.view.View;

import android.widget.ImageView;



public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

    }

    public void flipOnVertical(View thumbnailView) {
        ImageView thumbnail = (ImageView)thumbnailView;
        ImageView animatedImage = (ImageView) findViewById(R.id.animatedImage);
        //load animation file
        Animator animator
                = AnimatorInflater.loadAnimator(this, R.animator.flip_on_verticle);
        animator.setTarget(animatedImage);
        animator.start();
    }
}

Or you can do the animation programmatically without need to create animator res file as following:
 public void flipOnVertical(View thumbnailView) {
   ImageView thumbnail = (ImageView)thumbnailView; 
   ImageView animatedImage = (ImageView) findViewById(R.id.animatedImage);
 
   ObjectAnimator objectAnimator = ObjectAnimator.ofFloat(animatedImage ,"rotationY",   0.0f,360.0f);
   objectAnimator.setduration(5000);
   objectAnimator.start();
}

To see full project check the branch of feature/property-animation in my Github


###Introduction for RxJava for android developers
In this Post I am going to talk about RxJava for android.RxJava is one of the hottest topics nowadays because of its advantages over the classic way for android developing. RxJava is a library that allows us to represent any operation as an asynchronous data stream that can be created on any thread, declaratively composed, and consumed by multiple objects on any thread.

These data streams don't necessarily have to take the form of traditional data types. RxJava treats every thing as stream of data for example  variables to properties, caches, and even user input events like clicks and swipes.

The data emitted by each stream can either be a value, an error, or a "completed" signal, although you don’t necessarily have to implement the last two. Once you've created your data-emitting streams, you combine them with reactive objects that consume and then act on this data, performing different actions depending on what the stream has emitted.

RxJava has three core components:

Observable
Observer
Subscription
There are a lot of operators that manipulate data like mapping, filtering ..etc.Also there are schedulers where you can choose which thread you want to do your task and which other you will get the response .



To clear the idea behind RxJava ,Look at this picture for a moment  you will notice that there are a bunch of data (circles,diamonds and triangles) emitted by Observable and there is a filter (Operator)in the middle to filter data (shapes) according to some value(circle shape) and in the end you will get the filtered data in another level(Observer).So the main function of Observable is to observe for data and emit the data continuously .Also the main function of operator is to control the  observable .Finally ,the main function of Observer is to get data in its configured thread when it subscribe for it .

Let us make small comparison between the old fashion of Java and the RxJava style:

Example :Find the Odd Number in list of integers
The Java Style Like this:

public class data {

  static List<Integer> data;

  public static void main(String[] args) {

  printOddNums();

  }

static void printOddNums(){

data = new ArrayList<Integer>();

      data.add(1);

      data.add(2);

      data.add(3);

      data.add(4);

      data.add(5);

      data.add(6);

     for (int i = 0; i < data.size(); i++) {
         if(!(i%2==0))
            System.out.println(i +"is ODD Number");
      }

   }

}

We defined here an array list of integers and we make looping over the integers to check if integer number is odd to be printed.

Now, The RXJava Style Like this:
Observable<Integer> observable =

Observable.just(1, 2, 3, 4, 5,6)
.filter(new Func1<Integer, Boolean>() {
@Override
public Boolean call(Integer integer) {
//check if the number is odd? If the number is odd return true, to emmit that object.
return integer % 2 != 0;
}
});

Observer<Integer> observer = new Observer<Integer>() {
@Override
public void onCompleted() {
System.out.println("All data emitted.");
}

@Override
public void onError(Throwable e) {
System.out.println("Error received: " + e.getMessage());
}

@Override
public void onNext(Integer integer) {
System.out.println("New data received: " + integer);
}
};

Subscription subscription = observable
.subscribeOn(Schedulers.io()) //observable will run on IO thread.
.observeOn(AndroidSchedulers.mainThread()) //Observer will run on main thread.
.subscribe(observer); //subscribe the observer



We defined here an observable to  list of integers and we make filtering using operator called filter to    filter  the emitted integers for checking if them are odd to be printed or not.We defined observer to get emitted integers in OnNext method one by one and we printed it.We also defined the subscription object to enable observer to subscribe to steam to get integers in UI Thread  and to enable observable to do his operation in IOThread.

 Note:You should call unsubscribe when you finish your activity or fragment
 to close the stream of data like the following:
@Override
 public void onDestroy() {  
   super.onDestroy(); 
   //Unsubscribe both subscriptions.
   mSubscription.unsubscribe(); 
}
Finally, I would like to say that RxJava is  very useful  component and it adds new way of thinking while coding.You can use RxJava  every where in your code for example you can make timing tasks, Rest API Calls,background tasks, many dependent tasks ,functional programming and more.I hope you will find this article helpful .



In This post I am going to talk about RxJava operators.In the previous article  we got an introduction to RxJava. It is  a reactive library for the JVM that can help you to build data reactive apps.

Before we go deeply in this topic let us know what is the difference between RxJava2 and RxJava1.To know more about this, please  see this on RxJava Repository on GitHub .To summarize the difference ,You can say that RxJava2 is well written reactive programming library.RxJava2 is written from scratch on the top of Reactive concepts.It has better performance over RxJava1 and better memory management.

Introduction to RxJava Operators Concept:
RxJava Operator is a way to convert your Observable from form shape to another. RxJava has
enormous number of operators.No one expects you to memorize this list but it is worth to read them.You will find often an operator for every transform or change in your data.If you did not find some operator, you can do some operations on your observable until you get the desired operator.

In this article I will not cover all operators in RxJava but I will talk about the most popular and greatly used in work.

The first thing is to add Rxjava2 dependency in Cradle file.Please check latest version from GitHub repository.
compile 'io.reactivex.rxjava2:rxjava:2.0.5'

There are Categories for RxJava operators .I am going to talk about some of them like Observable creational operators,Filtering operators, combing operators and concurrency operators.

Observable Creational Operators
These operators control the creation of observable like emitting some of objects one by one ,emitting array of objects, emitting  object one by one after some delay ,emitting range of  items sequentially  and more.These are some of creational observable operators and their usage with examples:

Just  
is an operator which convert an object or several objects into an Observable that emits that object or those objects with out change of data like the following:

private Observable createObserableUsingJust(){
    return Observable.just(1,2,13,43,50);
}
The output of this method is observable object which emits the values of Just arguments one by one.

From
is an operator which converts an Iterable, a Future, or an Array into an Observable like the  following :

private Observable createObserableUsingForm(){
    return Observable.fromArray(new Integer[]{10,20,30,40,50});
}
The output of this method is observable object emits the array values one after another like Just operator.You will find more form operators like fromArray,fromFuture,fromIterable …etc.

Interval
is an operator which creates an Observable that emits a sequence of integers spaced by a given time interval like the following:

private Observable createObservableUsingInterval(){
    return Observable.interval(0,2, TimeUnit.SECONDS);
}

Filtering Operators
The main goal of these operators is to filter stream according to some condition to emit some objects like the following:

Filter
is an operator which filter items emitted by Observable like the following:

private Observable filter(){
    return Observable.just(1,2,3,4,5,6,7,8)
              .filter(new Predicate<Integer>() {
                  @Override
                  public boolean test(Integer num) throws Exception {
                      return num%2==0;
                  }
              });
}

The output of this method is observable with even numbers only because we apply
filter operator on number sequence.

Skip 

is an operator which ignores the first n items emitted by observable.
private Observable showFunctionOfSkip(){
    return Observable.fromArray(new Integer[]{1,2,3,4,5,6,7,8})
              .skip(2);
}

The output of this method is observable which contains numbers started from 3
to 8 and numbers 1,2 will be skipped.

Take 

is an operator which emits the first n items of observable
private Observable showFunctionOfTake(){
    return Observable.fromArray(new Integer[]{1,2,3,4,5,6,7,8})
            .take(2);
}

The output of this method is observable with 1,2 numbers only.
Combing Operators
The main goal of these operators is to combine two different sources of streams and emit them as a single source.And these are some of them:

Merge
is an operator which combines multiple observables into one.

private Observable showFunctionOfMerge(){
    String [] myName ={"Mahmoud","Ramadan","Abd","elwahed"} ;
    String [] myJob ={"I am ","Software Engineer"};

    Observable myNameObservable= Observable.fromArray(myName);
    Observable myJobObservable= Observable.fromArray(myJob);

    return Observable.merge(myNameObservable,myJobObservable);
}

Note:merge does not guarantee that the order of emitted data by observable unlike 
concat operator.

Zip
 is an operator which combines sets of items emitted by two or more Observables together via a specified function and emit items based on the results of this function
class CustomObject{
    int number;
    String ch;
}

private Observable<CustomObject> showFunctionOfZip(){

    Observable<Integer> numObservable = Observable.fromArray(new Integer[]{11, 22, 33, 44, 55});  //Emits integers
    Observable<String> chObservable = Observable.fromArray(new String[]{"S", "O", "O", "N",});  //Emits characters

    return Observable.zip(numObservable, chObservable, new BiFunction<Integer, String, CustomObject>() {
        @Override
        public CustomObject apply(Integer integer, String s) throws Exception {
            CustomObject customObject = new CustomObject();
            customObject.number=integer;
            customObject.ch = s;
            return customObject;
        }
    });

}
Transforming Operators
The main goal of these operators is to transform emitted data by Observable like the following:

map is an operator which transforms the items emitted by an Observable by applying a function to each of them

private Observable showMapFunction(){
    return Observable.just(1,2,3,4,5)
                     .map(new Function() {
                         @Override
                         public Object apply(Object ob) throws Exception {
                             return (Integer)ob*10;
                         }
                     });

}

The output of this method  is observable which its emitted values are multiplied with 10.

In the next Article I will continue the explanation of the rest operators.Please if you find this article helpful share it to your friends and give me your feedback through commenting on this article.
In this post I am going to talk about more RxJava operators.If you do not know about RxJava ,you can read the previous two articles from here:

Introduction 
RxJava2 Operators -part1
In the previous article we talked about creation, filtering and transforming of observables. We saw how it was awesome. So we are going to talk about the concurrency operators in this article.

RxJava Concurrency Operators
when you develop an application, you will need often  to do some tasks in parallel to prevent your app from crashing. Thanks to RxJava ,You can handle multi threading easily .RxJava helps you to avoid the painful handling of multithreading  using Java.You just need to define which thread you want to do your task and which thread you want to get the response. Concurrency operators like observeOn() and subscribeOn() make our life easy also schedulers.

Schedulers
Schedulers are used to execute some of work on a certain thread. Schedulers are abstraction of Android and Java threading.when you use scheduler t o do task ,scheduler will run on one of available threads of  thread pool(collection of threads that are ready to use).We can choose which thread using the operators observeOn() and subscribeOn().

There are many types of schedulers that you can use in RxJava. But I will list the most greatly used ones as follows:

AndroidSchedulers.mainThread()
This type creates scheduler which will execute its task on Android Main Thread. We often use it to get response for observer.

Schedulers.io()
This type creates and returns scheduler for I/O operations like reading/writing over database and network calling.These tasks are not CPU intensive.

Schedulers.newThread()
This type creates a new thread to do the task and return scheduler .you should take care when you use         this type because the new thread will not be reused after the task finished and it will be destroyed.

Schedulers.computation()
This type creates scheduler for CPU intensive operations like image filtering, complex  calculations. It uses the CPU cores so you should be careful when you use it.

Now ,we will talk about subscribeOn() and observeOn() operators.

subscribeOn() Operator
This operator tells the scheduler to do the task on observable upstream and then send response to observer on the same thread.You should not use multiple of subscribeOn() on the same chain for observable. Because your chain will choose the closets one to the observable source as follows

Observable.create(data())
                .subscribeOn(Schedulers.computation()) // this has effect
                .subscribeOn(Schedulers.io()) // this has no effect
 
Let us see example for subscribeOn()
private void showFunctionOfSubscribeOn(){
    Observable.just(100, 200, 300)
            .subscribeOn(Schedulers.newThread())
            .subscribe(getObserver());
}


private io.reactivex.Observer<Integer> getObserver(){
    io.reactivex.Observer<Integer> observer = new io.reactivex.Observer<Integer>() {
        @Override
        public void onSubscribe(Disposable d) {
            Log.e(TAG, "onSubscribe" + Thread.currentThread().getName());
        }

        @Override
        public void onNext(Integer integer) {
            Log.e(TAG, "onNext: " + value + Thread.currentThread().getName());
        }

        @Override
        public void onError(Throwable e) {
            Log.e(TAG, "onError: ");
        }

        @Override
        public void onComplete() {
            Log.e(TAG, "onComplete: All Done!" + Thread.currentThread().getName());
        }
    };
    return  observer;
} here we used Scheduler.newThread() to do task in another thread.Although we call subscribe on main thread but the observable worked on another thread. ObserverOn() Operator The main function of observerOn() is to switch the emission of observable to another thread or scheduler.We use this operator to tell downstream consumers to receive the subsequent emissions.Unlike subscribeOn operator, when you put observeOn operator you will affect the thread that observable uses.
Let us see example to understand this point.

In this post I am going to talk about RxBinding for android app development.In previous article we talked about some  RxJava2 operators related to Multithreading .We saw how to handle multiple threading using observeOn and subscribeOn and how to use schedulers according to our needs. But what about your UI events ,How many  times you implement OnclickListener or TextWatcher for EditText.Your code will be a lot of anonymous classes.Here RxBinding appears on the scene.

What is RxBinding ?
RxBinding is a set of libraries that helps you to handle user interface events through reactive paradigm.RxBinding enables you to convert any Android view event into Observable.To integrate RxBinding  for you code put the following in build.gradle for your app module.

compile 'io.reactivex.rxjava2:rxandroid:2.0.1'
compile 'io.reactivex.rxjava2:rxjava:2.0.8'
compile 'com.jakewharton.rxbinding2:rxbinding:2.0.0'

If you want to work with lambda expression add the following:
defaultConfig {
      ......................
        jackOptions {
            enabled true
        }
    }
    .....................
    compileOptions {
        sourceCompatibility JavaVersion.VERSION_1_8
        targetCompatibility JavaVersion.VERSION_1_8
    }
 
Now , let us see some examples for RxBinding:
Button Example
private Disposable loginBtnSub;

loginBtnSub = RxView.clicks(loginBtn).subscribe(new Consumer<Object>() {
 @Override
 public void accept(@NonNull Object o) throws Exception {
 Toast.makeText(MainActivity.this, "Hi, Mahmoud ", Toast.LENGTH_SHORT).show();
 }
});

……………
@Override
protected void onDestroy() {
    super.onDestroy();
    loginBtnSub.dispose();
}
We implemented the handling of click listener for button using subscription and we unsubscribe for it on onDestroy method.

EditText Example
edtUsernameSub = RxTextView.
        textChanges(edtUsername)
        .subscribe(new Consumer<CharSequence>() {
            @Override
            public void accept(@NonNull CharSequence charSequence) throws Exception {
             if(charSequence.toString().equalsIgnoreCase("mahmoud"))
                 Toast.makeText(MainActivity.this, "Hi mahmoud", Toast.LENGTH_SHORT).show();
            }
        });

@Override
protected void onDestroy() {
 super.onDestroy();
    edtUsernameSub.dispose();
}
Now , I know that you see there is no big different than the traditional way of listeners handling for views. But this is not true because the RxBinding gives you more options than the traditional way for instance convert any event to observable .Then, imagine what you can do on it like different operators to facilitate your coding .Also RxBinding gives you systematic way to deal with different views than many ways of view listeners in android.

RxBinding with RxJava operators

In this post I am going to talk about RxLifecycle  library form Trello . In the previous article we talked about RxBinding .We saw how to convert any UI event to observable.Then we  learned how to apply operators on these events. RxJava have enormous benefits but it has one big problem.The problem is Memory Leak that appears when system try to kill activity or fragment  and there is running observable and observer waiting for the response.So you want to handle subscription problem manually to dispose it or using  a good solution called Rxlifecycle library from Trello Company. The main objective of RxLifecycle is to terminate  the emitting sequence of observable by calling onNext() or onError() methods not terminating of subscription.

RxLifecycle Integration
add the following lines to build.gradle for app module
compile 'com.trello.rxlifecycle2:rxlifecycle:2.0.1'
compile 'com.trello.rxlifecycle2:rxlifecycle-android:2.0.1'
compile 'com.trello.rxlifecycle2:rxlifecycle-components:2.0.1'

To enable rxlifecycle for activity or fragment you should inherit from RxActivity,
RxAppcompatActivity or RxFragment.
import com.trello.rxlifecycle2.components.support.RxAppCompatActivity;

public class MainActivity  extends RxAppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }
When you want to bind an Observable to the lifecycle of an Activity or Fragment, you can specify the lifecycle event when observable should terminated or let the RxLifecycle  library to handle it. By default Rxlifecycle will termibnte observable sequencing in onDestroy()  for activity and onDetach() for fragment. You can leave this task for library like the following
@Override
    protected void onResume() {
        super.onResume();
        myObservable.compose(this.<Integer>bindToLifecycle()).subscribe();
    }
}

Alternatively, you can specify the lifecycle event where RxLifecycle should terminate an Observablesequence, using RxLifecycle.bindUntilEvent.



@Override
protected void onResume() {
    super.onResume();
    myObservable.compose(bindUntilEvent(ActivityEvent.DESTROY)).subscribe();
}
What is the Next?
In this article you saw how to use RxLifecycle library from Trello to handle memory leak for RxJava code. So what is the next?.You should try to implement what you learned in this series about RxJava .Also there are multiple useful libraries build using RxJava you can use them. I hope you enjoy this series and I will be happy if You can give me your feedback about this series and how can I improve it.





Realm
In this post I am going to talk about Realm database. Realm is a new fast  object database framework  written from the ground over C++. It is NoSQL database with better performance . It is so easy, fast and well documented. When you use Realm you will not use any sql statements longer.

Installation
Install Realm as a Gradle plugin.

Step 1: Add the class path dependency to the project level build.gradle file.

buildscript {
    repositories {
        jcenter()
    }
    dependencies {
        classpath "io.realm:realm-gradle-plugin:4.2.0"
    }
}
Step 2: Apply the realm-android plugin to the top of the application level build.gradle file.

apply plugin: 'realm-android'
Initializing Realm
create MyApp class that  extends from Application and add Realm.init(this);

/**
 * Created by Mahmoud Ramadan on 11/18/17.
 */

public class MyApp extends Application {

    @Override
    public void onCreate() {
        super.onCreate();
        Realm.init(this);
    }

    @Override
    public void onTerminate() {
        super.onTerminate();
    }

}

add MyApp class to your manifest file like the following:
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.ramadan_apps.realmtutorials">

    <application
        android:name=".MyApp"
        android:allowBackup="true"
        android:icon="@mipmap/ic_launcher"
        android:label="@string/app_name"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/AppTheme">
        <activity android:name=".MainActivity">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>

</manifest>
Storing Data in Realm is So Easy
To create Entity in Realm you want to define your model and extend from RealmOject like the following:

/**
 * Created by Mahmoud Ramadan on 11/18/17.
 */

public class Dog extends RealmObject {

    @PrimaryKey
    private int id;
    @Required
    private String name; // required field ,can not be null
    
    private int  age;

    public int getId() {
        return id;
    }

    public void setId(int id) {
        this.id = id;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }
}
This is A dog table with three columns id, name and age.The primary key is id and name is required field.To save dog object in realm ,you can do as follows.
    Dog dog = new Dog();
    dog.setId(1);
    dog.setName("jack"); dog.setAge(3);
Realm realm = Realm.getDefaultInstance();

try{
    realm.beginTransaction();
    realm.copyToRealm(dog);
    realm.commitTransaction();
}catch (Exception e){
 realm.cancelTransaction();
}
we saved dog object with name Rex and age =3 .You should have realm object before make transaction.Also you must do any database operation between realm.beginTransaction() and commitTransaction().But There is another recommended approach using executeTransaction which it cancels the transaction in case of error occurs.

realm.executeTransaction(new Realm.Transaction() {
    @Override
    public void execute(Realm realm) {
        realm.copyToRealm(dog);
    }
});
Retrieving Data from Realm

To retrieve data from query for dog table do the following:

//read
 RealmResults<Dog> dogs = realm.where(Dog.class).findAll();

This is query for realm to get all records in dog table.If you want to make conditional query you can use realm modifiers like equalTo().For Instance I want to get all dogs which are equal to 1 year.
//conditional query
RealmResults<Dog> dogs2 = realm.where(Dog.class).equalTo("age",1).findAll();

If you want to get the first record only just do the following:
Dog dog2 = realm.where(Dog.class).equalTo("age",1).findFirst();

Updating Realm Data

To update record for dog table do the following:

final Dog myDog = realm.where(Dog.class).equalTo("id",1).findFirst();
realm.executeTransaction(new Realm.Transaction() {
    @Override
    public void execute(Realm realm) {
        myDog.setName("mick");
        myDog.setAge(2);
    }
});
Deleting Realm Data
To delete All records in dog table do as follows:
//deleting realm
realm.executeTransaction(new Realm.Transaction() {
    @Override
    public void execute(Realm realm) {
        realm.delete(Dog.class);
    }
});

Note: You should close the connection to Realm when activity is going to destroy
like this
@Override
protected void onDestroy() {
    super.onDestroy();
    realm.close();
}

Finally ,I hope the first part of our series about Realm database was helpful for you.Your feedback is very important for me . Please share your feedback through commenting on this article.In The next article we will talk about Realm Modifiers and how to implement different relationships

In this post I am going to talk about Realm database relationships and modifiers. In the previous article we talked about an introduction to Realm database and we saw how it was  awesome , very simple and easy.Also we talked about simple CRUD operations like any database .

Realm Query Modifiers 
There are a lot of helpful modifiers which help you when making a query for you table like the following:

between()
greaterThan()
lessThan()
greaterThanOrEqualTo()
lessThanOrEqualTo()
equalTo()
notEqualTo()
contains()
beginsWith()
endsWith()
Realm Object Relationships
You can manage all relationships easily in realm like the following:

Many To One Relationship
Suppose family  have a cat  which is shared between all family members.So the all family members can say I have a cat so this relationships is Many To One . Now we have class Member that represents family member and we have cat class that represents cat and we can represent the relationship as the following:

public class Cat extends RealmObject {

    private String name;
    private int age;

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getAge() {
        return age;
    }

    public void setAge(int age) {
        this.age = age;
    }
}

public class Member extends RealmObject {

    private  String name;
    private Cat cat;

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public Cat getCat() {
        return cat;
    }

    public void setCat(Cat cat) {
        this.cat = cat;
    }
}

Member member1 = new Member();
Cat cat = new Cat();
cat.setName("bos");
cat.setAge(1);

member1.setCat(cat);

One To Many Relationship

Suppose I have  many cats called Coco,Fofo,Toto,etc. The relationship will be like the following:

public class Member extends RealmObject {

private String name;
private RealmList<Cat> cats;

public RealmList<Cat> getCats() {
return cats;
}

public void setCats(RealmList<Cat> cats) {
this.cats = cats;
}

public String getName() {

return name;
}

public void setName(String name) {
this.name = name;
}

}

Recursive Relationship

In some situations you need recursive relationship. For Instance, if I am instance from Person class and I ave many friends each one of them is instance of Person class like the following:

public class Person extends RealmObject {
    private String name;
    private RealmList<Person> friends;

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public RealmList<Person> getFriends() {
        return friends;
    }

    public void setFriends(RealmList<Person> friends) {
        this.friends = friends;
    }
}


Relationship Queries
Let say we have Person class with many cats one to many relationship and we want to find all persons who have "bos" cat name

RealmResults<Person> result = realm.where(person.class).equalTo("cats.name","bos").findAll();

finally I hope this article will be helpful for you. In the next article we will talk about Multithreading and using RxJava with .


In this post I am going to talk about using RxJava2 with Realm database to cache the endpoint response

to be available for offline case.If you do not know about RxJava2 you can check our series here;

This Demo will use many libraries like

Retrofit
RxJava2
Realm
Gson
Retrolambda
The Demo out will be like this following image



It is a list of my repos on Github.It displays the data if there is no internet from cache and displays cache before call endpoint if there is internet.Let's start with our required libraries as the following:

https://gist.github.com/mrabelwahed/5bf9042fcaaecd71c073b0502663894f

https://gist.github.com/mrabelwahed/c574bd7d36b65882677a5346ce7af86b

https://gist.github.com/mrabelwahed/450814c66a9e4f11507966207e1d4f07

The above are the build.gradle for project and app module where we define the required libraries.The next is manifest file with internet and access network permissions.Now we will create My App class which extends from Application class to be to handle realm configuration

https://gist.github.com/mrabelwahed/25fa20a1e2e8644eb9d526e29eb3b958

The following is the layout for main activity.It is a relative layout with recyclerview component.

https://gist.github.com/mrabelwahed/b077287d6cb7eba2da930a0c71b36b5b

we will need the Repo item view for recyclerview adapter as the following.It is simple layout with two textviews for repo name and repo id.

https://gist.github.com/mrabelwahed/7e51751fe844026b848429d646345348

now we will define the realm table which is the model for our retrofit request, for simplicity  I used only two attributes from json response for our demo. It is recommended to use @SerializedName("name_of_attribute_in _json_response") from GSON library as the following

https://gist.github.com/mrabelwahed/475a6e983ab94fb1c4c2d9c29760c049

Now we will create our ReposAdapter to display list of user repos as the following:

https://gist.github.com/mrabelwahed/4e617905132db6a676eacea2f2631d63

The following is the AppConst class to hold all constants in your app like the base url for our apis.

https://gist.github.com/mrabelwahed/4664dd7fb890aaf1afc51ca648668c58

Now we will define the repos end point for our demo in interface with @GET("") annotation for retrofit like and we will use Observable instead of Call because we want to use RxJava.This endpoint will take the username as input and returns Observable of repos of user  like the following:

https://gist.github.com/mrabelwahed/3d6059d53d65c5bc19a74811a60f9b8a

let's now define our ApiClient to be able call the previous endpoint.This ApiClient class follows the Singleton design pattern and it is configured with GsonConverter and RxJava2Adapter, also we use interceptor for Url logging.

https://gist.github.com/mrabelwahed/6d16130333d93cad43a3842c51116a84

finally the MainActivity with endpoint call and we using mergeWith()Operator because it emits the available observable (Network or Database) and does not guarantee  the order of observables.the idea is simple you hit the server and then save the response in realm in another thread then merge it with stream form database and if there is no internet connectivity you call the cache directly.I hope this article will be useful for you.please share it with your friends.

https://gist.github.com/mrabelwahed/0d5329390e8a724cd5c180d5e7515cf6


###build library and upload it to jitpack
In this post I am going to talk about how to build android library  and then we will publish it on Jitpack . Every android developer uses many libraries during the development like Retrofit,Glide,GSON,etc.Imagine your life if you don't use libraries I think that it will be like a nightmare.Well -known Libraries save your time with less bugs and enhanced performance.

Why should you write libraries?
As a developer, you should learn how to use high rank libraries in your code and also learn from their source code how to write clean code .The more you read source code of libraries, the more  you will be expert in android development and then try write your own libraries even if they are so simple.

Now, let us learn together how to create a library step by step .I am using Android studio '3.0.1' for this tutorial.

Step1: create a normal android studio project

Step2: add new module from file





Step3: add new library module



Step4:add library name and select min SDK APi



Now, you will find new module called "mylibrary" is added in your project.This module where you will write your library files and resources. For demo purpose,  I will make simple circle view .

Step5: create CircleView class in your library module


Step6:define circle view attributes


Step7: create layout for sample on app module not you library module


Step8:create Main Activity for Sample on App module


Now, we created our library and sample for using this library to help other developers  to use our library.

Step9:Publish your project to your Github account

open the terminal of your android studio project and write the following  commands after you created your GitHub repo.

git init

git add .

git commit -m "add circle view "

git remote add origin git@github.com:mrabelwahed/CircleView-Library.git

git push -u origin master







step10:create release  and name it for example "1.0"

  

Step10: add Jitpack plugin to your project

for your root build.gradle add the following

classpath 'com.github.dcendents:android-maven-gradle-plugin:2.0' // Add this line

in your library build.gradle add the following at the top of the file

apply plugin: 'com.github.dcendents.android-maven'

group='com.github.YourUsername'

Step 11: sync your project and push the changes to your repo.

Step 12: add topics (tags) for your library from GitHub repo to help developers to find your lib from the Github search

Step13:Go to Jitpack.io website  and enter you repo url on input field and click lookup, you will get the lib dependency url .Make sure to copy them to put them on your Readme.md file for your Github repo.



Step14: create Readme.md for your GitHub and put your features and documentation

Step15:create your suitable License for your repo.

 



finally ,I hope this tutorial will motivate you to start writing your own libraries.I will be happy if some one read this and apply it.








