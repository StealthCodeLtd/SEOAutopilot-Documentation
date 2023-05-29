# Google Cloud - setup

### Google Cloud API Settings

Required credentials:

* Friendly name
* Service account key (JSON File)

<figure><img src="../../../.gitbook/assets/Google Cloud.jpg" alt=""><figcaption></figcaption></figure>

### How to obtain credentials (JSON file)

Login in to your Google Cloud account.

Navigate: **Cloud Storage** > **Buckets**

<figure><img src="../../../.gitbook/assets/Google 1.jpg" alt=""><figcaption></figcaption></figure>

Create a new project and set **Project Name** and **Location**. Click "**Create**".

<figure><img src="../../../.gitbook/assets/Google 2.jpg" alt=""><figcaption></figcaption></figure>

Navigate: **Buckets** > **Create Bucket**

<figure><img src="../../../.gitbook/assets/Google 3.jpg" alt=""><figcaption></figcaption></figure>

Give a name for your bucket and click "**Continue**" button.&#x20;

<figure><img src="../../../.gitbook/assets/Google 4.jpg" alt=""><figcaption></figcaption></figure>

Continue by setting the next options based on your preference. On the step "**Choose how to control access objects**", on **Access control** set "**Uniform**" and continue.

<figure><img src="../../../.gitbook/assets/Google 5 (2).jpg" alt=""><figcaption></figcaption></figure>

Then navigate to **APIs & Services** > **Enabled APIs and Services**

<figure><img src="../../../.gitbook/assets/Google 6.jpg" alt=""><figcaption></figcaption></figure>

Click on "**ENABLE APIS AND SERVICES**"

<figure><img src="../../../.gitbook/assets/Google 7.jpg" alt=""><figcaption></figcaption></figure>

Select "**Cloud Storage API**" which is the service we will use for our cloud blogs.

<figure><img src="../../../.gitbook/assets/Google 8.jpg" alt=""><figcaption></figcaption></figure>

Click "**Enable**" button to enable the service.

<figure><img src="../../../.gitbook/assets/Google 9.jpg" alt=""><figcaption></figcaption></figure>

From "**APIs & Services**" > click on "**Credentials**" submenu.

<figure><img src="../../../.gitbook/assets/Google 10.jpg" alt=""><figcaption></figcaption></figure>

On **Credentials** menu, click "**CREATE CREDENTIALS**" and then "**Service Account**" option.

<figure><img src="../../../.gitbook/assets/Google 11.jpg" alt=""><figcaption></figcaption></figure>

You will be navigated to "**Service Account**" menu. Give a **Service account name** and **Service account ID** and click "**CREATE AND CONTINUE**" button to continue on next step.

<figure><img src="../../../.gitbook/assets/Google 12.jpg" alt=""><figcaption></figcaption></figure>

On the next step, you set **Role** to "**Owner**" and click "**DONE**" button.

<figure><img src="../../../.gitbook/assets/Google 13.jpg" alt=""><figcaption></figcaption></figure>

On the next screen you will see your service accounts. Click on your created service account.

<figure><img src="../../../.gitbook/assets/Google 14.jpg" alt=""><figcaption></figcaption></figure>

Go to "**KEYS**" menu, click on "**ADD KEY**"  and then "**Create new key**" option.

<figure><img src="../../../.gitbook/assets/Google 15.jpg" alt=""><figcaption></figcaption></figure>

On the pop-up menu you will see option on creating your private key. Choose "**JSON**" option and click "**CREATE**" button.

<figure><img src="../../../.gitbook/assets/Google 16 (1).jpg" alt=""><figcaption></figcaption></figure>

Save the JSON file on your system. Use this JSON file to setup Google Cloud service.