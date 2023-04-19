# Auto-GPT Twitter Plugin: Post Tweets

Elevate your social media presence with GPT-4 powered tweets. Compose, schedule, and automate engaging content for maximum impact.

## 🚀 Installation

Follow these steps to configure the Auto-GPT Twitter Plugin:

### 1. Clone the Auto-GPT-Twitter-Plugin repository
Clone this repository and navigate to the `Auto-GPT-Twitter-Plugin` folder in your terminal:

```bash
git clone https://github.com/riensen/Auto-GPT-Twitter-Plugin.git
```

### 2. Install required dependencies
Execute the following command to install the necessary dependencies:

```bash
pip install -r requirements.txt
```

### 3. Package the plugin as a Zip file
Compress the `Auto-GPT-Twitter-Plugin` folder or [download the repository as a zip file](https://github.com/riensen/Auto-GPT-Twitter-Plugin/archive/refs/heads/master.zip).

### 4. Install Auto-GPT
If you haven't already, clone the [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT) repository, follow its installation instructions, and navigate to the `Auto-GPT` folder.

### 5. Copy the Zip file into the Auto-GPT Plugin folder
Transfer the zip file from step 3 into the `plugins` subfolder within the `Auto-GPT` repo.

### 6. Locate the `.env.template` file
Find the file named `.env.template` in the main `/Auto-GPT` folder.

### 7. Create and rename a copy of the file
Duplicate the `.env.template` file and rename the copy to `.env` inside the `/Auto-GPT` folder.

### 8. Edit the `.env` file
Open the `.env` file in a text editor. Note: Files starting with a dot might be hidden by your operating system.

### 9. Add twitter configuration settings
Configure the following settings in the `.env` file:

```ini
################################################################################
### TWITTER API 
################################################################################

TW_CONSUMER_KEY=
TW_CONSUMER_SECRET=
TW_ACCESS_TOKEN=
TW_ACCESS_TOKEN_SECRET=
```
