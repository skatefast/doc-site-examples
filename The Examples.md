# Documentation techniques, examples, etc.

## Google
* [Organize your files in Google Drive](https://support.google.com/drive/answer/2375091?hl=en&ref_topic=2375187) - Collapsing dropdown menus for the four actions you can make with folders, done with Javascript. Navigation panel above to scroll through device type. Everything stays the same but the information that drops down. These dropdowns save space and direct users right to the action they need may need help performing; users don't need to read/scan as much. Very clean.

```
<div class="zippy-wrapper"><div class="zippy-container zippy-last"><a class="zippy index1 goog-zippy-collapsed" aria-expanded="false" href="javascript:;" role="button" aria-haspopup="true" st-ve="2" st-imp="" st-idx="1,4" st-ignore="">Create a folder</a></div>
  <div class="zippy-overflow"><div class="zippy-content zippy-hidden" style="margin-top: -156px; overflow: auto;" aria-hidden="true">
    <ol>
      <li>Open the Google Drive app.</li>
      <li>At the bottom right, tap Add <img src="//storage.googleapis.com/support-kms-prod/jGbiJw2tGliUWOsg332Sj8KxyEiv3nsqQSfm" width="18" height="18" alt="Add" title="Add">.</li>
      <li>Tap <strong>Folder</strong>.</li>
      <li>Name the folder.</li>
      <li>Tap <strong>OK</strong>.</li>
    </ol>
  </div></div>
</div>
```

