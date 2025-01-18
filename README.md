# YouTube Plus
A flexible enhancer for YouTube on iOS, featuring over hundred customizable options.

## Main Features
<li>Download videos, audio (including audio track selection), thumbnails, posts, and profile pictures</li>
<li>Copy video, comment, and post information</li>
<li>Interface customization: Remove feed elements, reorder tabs, enable OLED mode, and as use Shorts-only mode</li>
<li>Player settings: Gestures, default quality, preferred audio track</li>
<li>Save, Load and Restore settings. Clear cache once or automatically on app startup</li>
<li>Built-in SponsorBlock</li>
<li>And much, much more</li>
<br>


**YouTube Plus preferences can be found in the YouTube Settings**

**All contributors are listed in the Contributors section**

**Used open-source libraries are listed in the Open Source Libraries section**


## How to build a YouTube Plus app using Github actions
> [!NOTE]
> If this your first time, complete following steps before starting:
>
> 1. Fork this repository using the fork button on the top right
> 2. On your forked repository, go to **Repository Settings** > **Actions**, enable **Read and Write** permissions.

<details>
  <summary>How to build the YouTube Plus app</summary>
  <ol>
    <li>Click on <strong>Sync fork</strong>, and if your branch is out-of-date, click on <strong>Update branch</strong>.</li>
    <li>Navigate to the <strong>Actions tab</strong> in your forked repository and select <strong>Build YouTube Plus app</strong>.</li>
    <li>Click the <strong>Run workflow</strong> button located on the right side.</li>
    <li>Mark or unmark the tweaks you want to integrate. Learn more about them in the <a href="#tweak-integration-details">Tweak Integration Details</a> section.</li>
    <li>Prepare a decrypted .ipa file <em>(we cannot provide this due to legal reasons)</em>, then upload it to a file provider (e.g., filebin.net, filemail.com, or Dropbox is recommended). Paste the URL of the decrypted IPA file in the provided field.</li>
    <li><span style="color: red; font-weight: bold;">NOTE:</span> Make sure to provide a direct download link to the file, not a link to a webpage. Otherwise, the process will fail.</li>
    <li>Enter the tweak version from the releases (the latest release is selected by default).</li>
    <li>Make sure all inputs are correct, then click <strong>Run workflow</strong> to start the process.</li>
    <li>Wait for the build to finish. You can download the YouTube Plus app from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add /releases to the URL, i.e., github.com/user/YTLite/releases.)</li>
  </ol>
</details>
