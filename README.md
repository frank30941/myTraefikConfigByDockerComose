# myTraefikConfigByDockerComose

---

# Set ".env" file
``` sh
CODEUSER=XXX
TRAEFIKDOMAINNAME=XXX
EMAIL=XXX
BASICAUTH='XXX'
```

about the "BASICAUTH", you must use "htpasswd" to grenerate your password.
``` sh
echo $(htpasswd -nb ${USER} ${PASSWORD})
```
