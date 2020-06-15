# myTraefikConfigByDockerComose

---

# Set ".env" file
``` sh
CODEUSER=XXX
TRAEFIKURL=XXX
EMAIL=XXX
BASICAUTH='XXX'
```

about the "HTTPSAUTHPWD", you must use "htpasswd" to grenerate your password.
``` sh
echo $(htpasswd -nb user ${PASSWORD})
```
