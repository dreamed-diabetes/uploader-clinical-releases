# uploader-clinical-releases
This repository would include only the clinical uploader releases

### Deploy Uploader In Clinical Mode:

1.In the package.json file set the repository to dreamed-diabetes/uploader-clinical-releases.

2.Update In App.js file configure serverdata.Production with the Clinical Urls: `API_URL, UPLOAD_URL, DATA_URL, BLIP_URL, DREAMED_DMS_URL, DREAMED_DMS_CLIENT_ID, DREAMED_DMS_CLIENT_SECRET`.

3.In .config.js file configure the exports with the Clinical Urls too the same as in `2`.

4.Run yarn package with the local configuration, GH_TOKEN should be in the local .env, in Windows deployment the yubikey should be used too.

5.Add release notes to the new draft created and publish release.
