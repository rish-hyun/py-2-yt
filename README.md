# Python-to-YouTube

This script is updated and able to run for **python 3.x**
### Videos posted through YouTube API(using the script) will be private unless your account is _**approved and verified!**_
<hr>

Pre-requisites
* Create account on [Google CLoud Console](https://console.cloud.google.com/)
* download `client_secrets.json` after creating **OAuth 2.0 Client ID**

<br>

Dependencies
(Tested on Google Colab)
```python
pip install --upgrade google-api-python-client
pip install --upgrade google-auth-oauthlib google-auth-httplib2
```

<hr>

Using the [script](https://github.com/rish-hyun/py-2-yt/blob/main/py_2_yt.py)

`client_secrets.json` _should be in the directory of the script_
```python
!python py_2_yt.py --file=video_file.mp4\
                       --title="<Video Title>"\
                       --description="<Video Description>"\
                       --keywords="<Video Tags (comma separated)>"\
                       --category="<(Integer) corresponding to different categories>"\
                       --privacyStatus="<private/public>"
```
