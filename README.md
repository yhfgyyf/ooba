A headless [**Oobabooga**](https://github.com/oobabooga/text-generation-webui) wrapper.


Ensure you have installed Open-interpreter first.
<br>

I have made a few (experimental) fixes Windows:

https://github.com/KillianLucas/ooba/pull/8
https://github.com/KillianLucas/ooba/pull/6
https://github.com/KillianLucas/ooba/pull/7

- After installing Open-interpreter
```shell
pip install open-interpreter
```
- Run
```shell
pip install git+https://github.com/Notnaton/ooba.git@windows --force-reinstall
```

This will download and install some patches I have made for Ooba.
You can check the code here: https://github.com/Notnaton/ooba/tree/windows
This is experimental and will be updated at random times. 
Should you have a problem please run: `interpreter --local --debug` 

You can remove changes by running 
```shell 
pip install ooba --force-reinstall
```
