# easyVerein OpenID Connect example

This package showcases how to use the new [easyVerein](https://easyverein.com) Identity Provider feature.
It's based on Python 3.12 and uses `FastAPI`.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Create a venv and run:

```bash
pip3 install -r requirements.txt
```

Set the environment variables `client_id` and `client_secret`.
Then start the package using:

```bash
fastapi dev main.py --port 8090
```

Navigate with your browser to `http://localhost:8090/oauth/providers` and login using easyVerein :)

### Hint

The CORS settings of easyVerein require the client to be accessible via HTTPS. This is currently not enforced in Firefox, so for testing purposes you can use Firefox.
You can also use our test client on [https://oidc.tools.sd-server.de](https://oidc.tools.sd-server.de).

---

[easyVerein](https://easyverein.com) is a product of [SD Software-Design GmbH](https://software-design.de) · [MIT License](LICENSE)
