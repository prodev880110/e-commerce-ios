# ecommerce-app

<h1>E-commerce iOS App</h1>

This is a basic e-commerce app, including an additional targen for the Admin app that allows you to add edit and remove products and categories. This project is done as a submission project for the graduation course of iOS application development.

<h1>Getting started</h1>

<p>These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system. </p>

<h3>You will need</h3>
<ul> 
    <li>CocoaPods</li>
    <li>firebase 2 Project one for client App and one for Admin App</li>
    <li>PayPal acount</li>
    <li>braintree payments for Pay with PayPal</li>
</ul>

<h3>Installing</h3>

Download the project folder or clone the repo.

<pre>
<code>
git clone https://github.com/prodev880110/e-commerce-ios.git
</code>
</pre>

<h3>firebase</h3>
<p>
    Create your Project in firebase, <br>
    and register two Apps <br>
    for client App: <b>com.aminovavi.ecommerce-app</b> <br>
    for Admin App: <b>com.aminovavi.ecommerce-admin</b> <br><br>
    add GoogleService-Info.plist to project 
</p>

<p>
   in Authentication enable Email/Password<br>
    and open option Cloud Firestore
</p>

<br>
    
<h3>CocoaPods</h3>
<p>
  in project folder open terminal and run
</p>

<pre>
<code>
    pod install
</code>
</pre>


<h3>PayPal and Braintree</h3>
<p>
  in PayPal business acount create demo user (senbox user), and  linked to a Braintree user in Braintree dashboard
</p>



