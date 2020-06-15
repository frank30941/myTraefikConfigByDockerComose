# myTraefikConfigByDockerComose

---

# Set ".env" file
``` sh
CODEUSER=XXX
TRAEFIKURL=XXX
EMAIL=XXX
HTTPSAUTHPWD=XXX
```

about the "HTTPSAUTHPWD", you must use "htpasswd" to grenerate your password.
``` sh
echo $(htpasswd -nb user ${PASSWORD}) | sed -e s/\\$/\\$\\$/g
```
