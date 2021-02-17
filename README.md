<section><div name="STEP1:CreateYourFreeTrialAccount" data-unique="STEP1:CreateYourFreeTrialAccount"></div><h2 id="step1createyourfreetrialaccount" class="minus" tabindex="0"><strong>STEP 1</strong>: Create Your Free Trial Account</h2><p style="display: block;">If you already have a cloud account, skip to <strong>STEP 2</strong>.</p><ol style="display: block;">
<li><p>Open up a web browser to access the Oracle Cloud account registration form at <a href="https://myservices.us.oraclecloud.com/mycloud/signup?language=en" target="_blank">oracle.com/cloud/free</a>.</p></li>
<li><p>You will be presented with a registration page.
   <figure><img src="https://user-images.githubusercontent.com/42166489/108174321-4c22a680-7125-11eb-8d4d-9cba33694730.png" alt=""></figure></p></li>
<li><p>Enter the following information to create your Oracle Cloud Free Tier account.</p>
<ul>
<li>Choose your <strong>Country</strong></li>
<li>Enter your <strong>Name</strong> and <strong>Email</strong>.</li></ul></li>
<li><p>Once you have entered a valid email address, select the <strong>Verify my email</strong> button.
The screen will appear as follows after you select the button:
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/verify-email.png" alt=""></figure></p></li>
<li><p>Go to your email. You will see an account validation email from Oracle in your inbox. The email will be similar to the following:
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/verification-mail.png" alt=""></figure></p></li>
<li><p>Select the link (if possible) or copy and paste the link into your browser.</p></li>
<li><p>Enter the following information to create your Oracle Cloud Free Tier account.</p>
<ul>
<li>Choose a <strong>Password</strong></li>
<li>Enter your <strong>Company Name</strong></li>
<li>Your <strong>Cloud Account Name</strong> will generate automatically based on your inputs, you can change that name by entering a new value. Remember what you wrote. You'll need this name later to sign in.</li>
<li>Choose a <strong>Home Region</strong>.  Your Home Region cannot be changed once you sign-up.</li>
<li>Click <strong>Continue</strong>
<figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/account-info.png" alt=""></figure></li></ul></li>
<li><p>Enter your Address information.  Click <strong>Continue</strong>.
      <figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/cloud-native/setup-cloud-env/images/Introduction to Cloud Native _ Prerequisites_files/free-tier-address.png" alt=""></figure></p></li>
<li><p>Choose your country and enter a mobile member for verification.   Click the <strong>Text me a code</strong> button.</p>
<p><figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/free-tier-address-2.png" alt=""></figure></p></li>
<li><p>Once you receive your code, enter it and click <strong>Verify My Code</strong>.
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/free-tier-address-4.png" alt=""></figure></p></li>
<li><p>Click the <strong>Add payment verification method</strong> button.
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/free-tier-payment-1.png" alt=""></figure>  </p></li>
<li><p>Choose the verification method.  In this case click the <strong>Credit Card</strong> button. Enter your information and payment details.  <em>Note: This is a free credit promotion account. You will not be charged unless you elect to upgrade the account</em>.
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/free-tier-payment-2.png" alt=""></figure></p></li>
<li><p>Once your payment verification is complete.  Review and accept the agreement by clicking the check box.  Click the <strong>Start my free trial</strong> button.
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/free-tier-agreement.png" alt=""></figure></p></li>
<li><p>Your account is provisioning and should be available in a few seconds! When it's ready, you're automatically taken to a sign-in page. You'll also receive two emails from Oracle. One email will be the initial notification that provisioning is underway. The other email will be notification that provisioning is complete. Here is a copy of the final notification:
   <figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/account-provisioned.png" alt=""></figure></p></li>
</ol></section>

<section><div name="STEP2:SignintoYourAccount" data-unique="STEP2:SignintoYourAccount"></div><h2 id="step2signintoyouraccount" class="minus" tabindex="0"><strong>STEP 2</strong>: Sign in to Your Account</h2><p style="">If you've signed out of the Oracle Cloud, use these steps to sign back in.</p><ol style="">
<li><p>Go to <a href="https://cloud.oracle.com" target="_blank">cloud.oracle.com</a> and Enter your Cloud Account Name and click <strong>Next</strong>. This is the name you chose while creating your account in the previous section. It's NOT your email address. If you've forgotten the name, see the confirmation email.</p>
<p><figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/cloud-oracle.png" alt=""></figure></p></li>
<li><p>Expand the arrow after <em>"Oracle Cloud Infrastructure Direct Sign-In"</em> to reveal the login input fields.</p>
<p><figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/cloud-login-tenant.png" alt=""></figure></p></li>
<li><p>Enter your Cloud Account credentials and click <strong>Sign In</strong>. Your username is your email address. The password is what you chose when you signed up for an account.</p>
<p><figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/oci-signin.png" alt=""></figure></p></li>
<li><p>You are now signed in to Oracle Cloud!</p>
<p><figure><img src="https://oracle.github.io/learning-library/common/labs/cloud-login/images/oci-console-home-page.png" alt=""></figure></p></li>
</ol>


## Introduction
  In this workshop we will create a compute instance, download a script to configure streaming service, publish and consume messages. The Oracle Cloud Infrastructure Streaming service provides a fully managed, scalable, and durable storage solution for ingesting continuous, high-volume streams of data that you can consume and process in real time. Streaming can be used for messaging, ingesting high-volume data such as application logs, operational telemetry, web Click-stream data, or other use cases in which data is produced and processed continually and sequentially in a publish-subscribe messaging model.

## About Oracle Cloud Infrastructure Streaming Service
  The Oracle Cloud Infrastructure Streaming service provides a fully managed, scalable, and durable storage solution for ingesting continuous, high-volume streams of data that you can consume and process in real time. Streaming can be used for messaging, ingesting high-volume data such as application logs, operational telemetry, web click-stream data, or other use cases in which data is produced and processed continually and sequentially in a publish-subscribe messaging model.
  
 <main class="hol-Content" id="module-content"><article><h1 id="createsshkeysusingoraclecloudshell">Create SSH Keys Using Oracle Cloud Shell</h1>
<section><div name="Introduction" data-unique="Introduction"></div><h2 id="introduction">Introduction</h2><p>The SSH (Secure Shell) protocol is a method for secure remote login from one computer to another. SSH enables secure system administration and file transfers over insecure networks using encryption to secure the connections between endpoints. SSH keys are an important part of securely accessing Oracle Cloud Infrastructure compute instances in the cloud.</p><p>We recommend you use the <em>Oracle Cloud Shell</em> to interface with the OCI compute instance you will create. Oracle Cloud Shell is browser-based, does not require installation or configuration of software on your laptop, and works independently of your network setup.</p><p><em>IMPORTANT:  If the SSH key is not created correctly, you will not be able to connect to your environment and will get errors.  Please ensure you create your key properly.</em></p></section>



<section><div name="OracleCloudShell" data-unique="OracleCloudShell"></div><button id="btn_toggle" class="hol-ToggleRegions minus">Collapse All Steps</button><h2 id="oraclecloudshell" class="minus" tabindex="0">Oracle Cloud Shell</h2><p style="">The Cloud Shell machine is a small virtual machine running a Bash shell which you access through the OCI Console (Homepage). Cloud Shell comes with a pre-authenticated OCI CLI (Command Line Interface), set to the Console tenancy home page region, as well as up-to-date tools and utilities. To use the Cloud Shell machine, your tenancy administrator must grant the required IAM (Identity and Access Management) policy.</p><ol style="">
<li><p>To start the Oracle Cloud shell, go to your Cloud console and click the cloud shell icon at the top right of the page.</p>
<p><figure><img src="https://raw.githubusercontent.com/oracle/learning-library/master/common/labs/generate-ssh-key-cloud-shell/./images/cloudshellopen.png" alt=""></figure></p>
<p><figure><img src="https://raw.githubusercontent.com/oracle/learning-library/master/common/labs/generate-ssh-key-cloud-shell/./images/cloudshellsetup.png" alt=""></figure></p>
<p><figure><img src="https://raw.githubusercontent.com/oracle/learning-library/master/common/labs/generate-ssh-key-cloud-shell/./images/cloudshell.png" alt=""></figure></p></li>
<li><p>Once the cloud shell has started, enter the following commands. Choose the key name you can remember. This will be the keyname you will use to connect to any compute instances you create. Press Enter twice for no passphrase.</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">mkdir .ssh</span>
</code></pre>
<p><figure><img src="https://raw.githubusercontent.com/oracle/learning-library/master/common/labs/generate-ssh-key-cloud-shell/./images/mkdir.png" alt=""></figure> </p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">cd .ssh</span>
</code></pre>
<pre><code>ssh-keygen -b 2048 -t rsa -f &lt;&lt;sshkeyname&gt;&gt;
</code></pre>
<p><em>Note: The angle brackets &lt;&lt;&gt;&gt; should not appear in your code.</em></p>
<p><figure><img src="https://raw.githubusercontent.com/oracle/learning-library/master/common/labs/generate-ssh-key-cloud-shell/./images/cloudshell-ssh.png" alt=""></figure></p></li>
<li><p>Examine the two files that you just created.</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">ls</span>
</code></pre>
<p><figure><img src="https://raw.githubusercontent.com/oracle/learning-library/master/common/labs/generate-ssh-key-cloud-shell/./images/ls.png" alt=""></figure></p>
<p>Note in the output that there are two files, a <em>private key:</em> <code>&lt;&lt;sshkeyname&gt;&gt;</code> and a <em>public key:</em> <code>&lt;&lt;sshkeyname&gt;&gt;.pub</code>. Keep the private key safe and don't share its content with anyone. The public key will be needed for various activities and can be uploaded to certain systems as well as copied and pasted to facilitate secure communications in the cloud.</p></li>
<li><p>To list the contents of the public key, use the cat command:</p>
<pre><code> cat &lt;&lt;sshkeyname&gt;&gt;.pub
</code></pre>
<p><em>Note: The angle brackets &lt;&lt;&gt;&gt; should not appear in your code.</em></p>
<p><figure><img src="https://raw.githubusercontent.com/oracle/learning-library/master/common/labs/generate-ssh-key-cloud-shell/images/cat.png" alt=""></figure></p></li>
<li><p>Copy the contents of the public key and save it somewhere for later. When pasting the key into the compute instance in future labs, make sure that you remove any hard returns that may have been added when copying. <em>The .pub key should be one line.</em></p>
<p><figure><img src="https://raw.githubusercontent.com/oracle/learning-library/master/common/labs/generate-ssh-key-cloud-shell/images/copy-cat.png" alt=""></figure></p></li>



<article><h1 id="deployingocistreamingservice">Deploying OCI Streaming Service</h1>
<section><div name="Introduction" data-unique="Introduction"></div><h2 id="introduction">Introduction</h2><p>In this lab, we will create a compute instance, download a script to configure streaming service, publish and consume messages. The Oracle Cloud Infrastructure Streaming service provides a fully managed, scalable, and durable storage solution for ingesting continuous, high-volume streams of data that you can consume and process in real time. Streaming can be used for messaging, ingesting high-volume data such as application logs, operational telemetry, web Click-stream data, or other use cases in which data is produced and processed continually and sequentially in a publish-subscribe messaging model.</p></section>

<section><div name="STEP1:DownloadScripttoconfigureStreamingserviceandPublishmessages" data-unique="STEP1:DownloadScripttoconfigureStreamingserviceandPublishmessages"></div><button id="btn_toggle" class="hol-ToggleRegions plus">Expand All Steps</button><h2 id="step1downloadscripttoconfigurestreamingserviceandpublishmessages" class="plus" tabindex="0"><strong>STEP 1</strong>: Download Script to configure Streaming service and Publish messages</h2><ol style="display:none;">
<li><p>In Oracle Cloud Shell, configure OCI CLI:</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">oci setup config</span>
</code></pre>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/deploying-oci-streaming-service/deploying-oci-streaming-service/imagesoci-cli-config.png" alt=""></figure></p></li>
<li><p>Accept the default directory location. For user's OCID switch to OCI Console window. Click your person icon in the upper right, and select your user name. In the user details page Click <strong></strong> to copy the OCID. <strong>Also note down your region name as shown in OCI Console window</strong>. Paste the user OCID into Cloud Shell.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/deploying-oci-streaming-service/deploying-oci-streaming-service/imagesStream_004.PNG" alt=""></figure></p></li>
<li><p>Repeat the step to find tenancy OCID (person icon followed by selecting Tenancy Name). Paste the Tenancy OCID in Cloud Shell. Then enter the string that matches your region (us-ashburn-1, us-phoenix-1, etc).</p></li>
<li><p>When asked for <strong>Do you want to generate a new API Signing RSA key pair?</strong> answer Y.</p></li>
<li><p>Enter a passphrase you can remember.</p></li>
<li><p>When asked <strong>Do you want to write your passphrase to the config file?</strong> answer y.</p></li>
<li><p><strong>oci setup config</strong> also generated an API key. We will need to upload this API key into our OCI account for authentication of API calls. Switch to ssh session to compute instance, to display the content of API key Enter command:</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">cat ~/.oci/oci_api_key_public.pem</span>
</code></pre></li>
<li><p>Highlight and copy the content from ssh session. Switch to OCI Console, Click Human icon followed by your user name. In user details page Click <strong>Add Public Key</strong>. In the dialog box paste the public key content and Click <strong>Add</strong>.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/deploying-oci-streaming-service/deploying-oci-streaming-service/imagesStream_006.PNG" alt=""></figure></p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/deploying-oci-streaming-service/deploying-oci-streaming-service/imagesadd-public-api-key.png" alt=""></figure></p></li>
<li><p>Download and Install pip utility which will be used to install additional software. Enter command:</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py</span>
</code></pre>
<p>followed by</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">python get-pip.py</span>
</code></pre></li>
<li><p>Install a virtual environment. This is being done so we have a clean environment to execute our python script that will create and publish messages to OCI streaming service. Enter command:</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">pip install virtualenv</span>
</code></pre></li>
<li><p>Now create a virtual environment, Enter command:</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">virtualenv &lt;Environment_Name&gt;</span>
</code></pre>
<p>For example <strong>virtualenv stream_env</strong>.</p>
<p>Now initialize the virtual environment, Enter command:</p>
<p><strong>NOTE</strong> : Below command assumes that the environment name is 'stream-env'</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">cd ~/stream_env/bin</span>
</code></pre>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">source ~/stream_env/bin/activate</span>
</code></pre></li>
<li><p>Once your virtual environment is active, OCI can be installed using pip, Enter command:</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">pip install oci</span>
</code></pre>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/deploying-oci-streaming-service/deploying-oci-streaming-service/imagesinstall-stream.png" alt=""></figure></p></li>
<li><p>Now download the main script file though first we will remove the existing file, Enter Command:</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">cd ~</span>
</code></pre>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">rm stream_example.py</span>
</code></pre>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">wget https://objectstorage.us-ashburn-1.oraclecloud.com/p/7lS9G-yeYtB9bsUsW8cy813YjWgThlss2jed_DXKWcA/n/c4u03/b/oci-library/o/stream_example.py</span>
</code></pre></li>
<li><p>Now download a dependent script file though first we will remove the existing file, Enter Command:</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">cd ~/stream_env/lib/python2.7/site-packages/oci/streaming/</span>
</code></pre>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">rm stream_admin_client_composite_operations.py</span>
</code></pre>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">wget https://objectstorage.us-ashburn-1.oraclecloud.com/p/t9ftcmjIBMusNuJ2GPQlXR7LrwHLTGGJqi80amvV0pE/n/c4u03/b/oci-library/o/stream_admin_client_composite_operations.py</span>
</code></pre></li>
<li><p>Our setup is now ready. Before running the script switch to OCI Console window, from the main menu click <strong>Identity</strong> -&gt; <strong>Compartments</strong>. Select your compartment name and copy the OCID of the compartment.</p></li>
<li><p>In Cloud Shell, enter:</p>
<pre><button class="copy-button" title="Copy text to clipboard"></button><code><span class="copy-code">python ~/stream_example.py &lt;COMPARTMENT_OCID&gt;</span>
</code></pre>
<p>For example :</p>
<p>python ~/stream_example.py ocid1.compartment.oc1..aaaaaaaada2gaukcqoagqoshxq2pyt6cdsj2mhnrz3p5nke33ljx2bp476wq</p></li>
<li><p>Follow the prompts of the script. The script will create Streaming service called <strong>SdkExampleStream</strong>. It will publish 100 messages, create 2 groups on the compute and read those messages. Finally it will delete the streaming service. <strong>You will be prompted to hit enter after verifying each step</strong>.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/deploying-oci-streaming-service/deploying-oci-streaming-service/imagesdelete-stream.png" alt=""></figure></p></li>
</ol></section>

<section><div name="STEP2:Deletetheresources" data-unique="STEP2:Deletetheresources"></div><h2 id="step2deletetheresources" class="plus" tabindex="0"><strong>STEP 2</strong>: Delete the resources</h2><ol style="display:none;">
<li><p>Switch to OCI console window.</p></li>
<li><p>If your Compute instance is not displayed, From OCI services menu Click <strong>Instances</strong> under <strong>Compute</strong>.</p></li>
<li><p>Locate compute instance, Click Action icon and then <strong>Terminate</strong>.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/deploying-oci-streaming-service/deploying-oci-streaming-service/images/RESERVEDIP_HOL0016.PNG" alt=""></figure></p></li>
<li><p>Make sure Permanently delete the attached Boot Volume is checked, Click <strong>Terminate Instance</strong>. Wait for instance to fully Terminate.</p>
<p><figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/deploying-oci-streaming-service/deploying-oci-streaming-service/images/RESERVEDIP_HOL0017.PNG" alt=""></figure></p></li>
<li><p>From OCI services menu Click <strong>Virtual Cloud Networks</strong> under Networking, list of all VCNs will appear.</p></li>
<li><p>Locate your VCN , Click Action icon and then <strong>Terminate</strong>. Click <strong>Terminate All</strong> in the Confirmation window. Click <strong>Close</strong> once VCN is deleted.
 <figure><img src="https://oracle.github.io/learning-library/oci-library/oci-hol/deploying-oci-streaming-service/deploying-oci-streaming-service/images/RESERVEDIP_HOL0018.PNG" alt=""></figure></p></li>
</ol></section>

</article>
