# Ahmed-Abas-new
import base64
de="I0J5IEFobWVkIEFiYXMKdj0iIFwwMzNbMDszNW0gIgpwcmludCh2KyJUaGlzIHNjcmlwdCB3YXMgY3JlYXRlZCBieSBlbmdpbmVlcmluZyBBaG1lZCBBYmFzIikKVyA9J1wwMzNbMTszNm0qSGVsbG8gSWFtIEFobWVkIEFiYXMgd2VsY29tIG9uIG15c2NyaXAgJwpwcmludCgnJydcMDMzWzA7MzNtICoKIOKWiOKWiOKWiOKWiOKWiOKVlyAgICAg4paI4paI4pWXICDilojilojilZcgICAg4paI4paI4paI4pWXICAg4paI4paI4paI4pWXICAgIOKWiOKWiOKWiOKWiOKWiOKWiOKWiOKVlyAgICDilojilojilojilojilojilojilZcgICAgIArilojilojilZTilZDilZDilojilojilZcgICAg4paI4paI4pWRICDilojilojilZEgICAg4paI4paI4paI4paI4pWXIOKWiOKWiOKWiOKWiOKVkSAgICDilojilojilZTilZDilZDilZDilZDilZ0gICAg4paI4paI4pWU4pWQ4pWQ4paI4paI4pWXICAgIArilojilojilojilojilojilojilojilZEgICAg4paI4paI4paI4paI4paI4paI4paI4pWRICAgIOKWiOKWiOKVlOKWiOKWiOKWiOKWiOKVlOKWiOKWiOKVkSAgICDilojilojilojilojilojilZcgICAgICDilojilojilZEgIOKWiOKWiOKVkSAgICAK4paI4paI4pWU4pWQ4pWQ4paI4paI4pWRICAgIOKWiOKWiOKVlOKVkOKVkOKWiOKWiOKVkSAgICDilojilojilZHilZrilojilojilZTilZ3ilojilojilZEgICAg4paI4paI4pWU4pWQ4pWQ4pWdICAgICAg4paI4paI4pWRICDilojilojilZEgICAgCuKWiOKWiOKVkSAg4paI4paI4pWRICAgIOKWiOKWiOKVkSAg4paI4paI4pWRICAgIOKWiOKWiOKVkSDilZrilZDilZ0g4paI4paI4pWRICAgIOKWiOKWiOKWiOKWiOKWiOKWiOKWiOKVlyAgICDilojilojilojilojilojilojilZTilZ0gICAgCuKVmuKVkOKVnSAg4pWa4pWQ4pWdICAgIOKVmuKVkOKVnSAg4pWa4pWQ4pWdICAgIOKVmuKVkOKVnSAgICAg4pWa4pWQ4pWdICAgIOKVmuKVkOKVkOKVkOKVkOKVkOKVkOKVnSAgICDilZrilZDilZDilZDilZDilZDilZ0gICAgIAogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAKIOKWiOKWiOKWiOKWiOKWiOKVlyAgICAg4paI4paI4paI4paI4paI4paI4pWXICAgICAg4paI4paI4paI4paI4paI4pWXICAgICDilojilojilojilojilojilojilojilZcgICAgICAgICAgICAgICAgICAgCuKWiOKWiOKVlOKVkOKVkOKWiOKWiOKVlyAgICDilojilojilZTilZDilZDilojilojilZcgICAg4paI4paI4pWU4pWQ4pWQ4paI4paI4pWXICAgIOKWiOKWiOKVlOKVkOKVkOKVkOKVkOKVnSAgICAgICAgICAgICAgICAgICAK4paI4paI4paI4paI4paI4paI4paI4pWRICAgIOKWiOKWiOKWiOKWiOKWiOKWiOKVlOKVnSAgICDilojilojilojilojilojilojilojilZEgICAg4paI4paI4paI4paI4paI4paI4paI4pWXICAgICAgICAgICAgICAgICAgIArilojilojilZTilZDilZDilojilojilZEgICAg4paI4paI4pWU4pWQ4pWQ4paI4paI4pWXICAgIOKWiOKWiOKVlOKVkOKVkOKWiOKWiOKVkSAgICDilZrilZDilZDilZDilZDilojilojilZEgICAgICAgICAgICAgICAgICAgCuKWiOKWiOKVkSAg4paI4paI4pWRICAgIOKWiOKWiOKWiOKWiOKWiOKWiOKVlOKVnSAgICDilojilojilZEgIOKWiOKWiOKVkSAgICDilojilojilojilojilojilojilojilZEgICAgICAgICAgICAgICAgICAgCuKVmuKVkOKVnSAg4pWa4pWQ4pWdICAgIOKVmuKVkOKVkOKVkOKVkOKVkOKVnSAgICAg4pWa4pWQ4pWdICDilZrilZDilZ0gICAg4pWa4pWQ4pWQ4pWQ4pWQ4pWQ4pWQ4pWdICAgICAgICAgICAgICAgICAgIAogICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAgICAKJycnKQpwcmludCgiXDAzM1swOzMybSAqIHdlbGNvbWUgaW4gQWhtZWQgQWhtZCBBYmFzIHNjcmlwdCIpCnByaW50KCIjIyMjIyNBaG1lZEFic3Mgc2NyaXB0IHdhc2xhIHYxIyMjIyMjIikKcHNzPXN0cihpbnB1dCgiXDAzM1swOzM2bVvigKJcMDMzWzA7MzZtRW50ZXIgdGhlIHBhc3N3b3JkOiIpKQoKaWYgcHNzID09IkFobWVkNTAwNTUiOgogcGFzcwppbXBvcnQgd2ViYnJvd3Nlcgpmcm9tIHRpbWUgaW1wb3J0IHNsZWVwCnRlc3QgPSAnaHR0cHM6Ly93d3cuZmFzdC5jb20nCnByaW50KFcpCnY9NQpmb3IgdiBpbiByYW5nZSgxMDAwMDAwMDAwMDAwKSA6CiAgICBzbGVlcCgzMCkKICAgIHdlYmJyb3dzZXIub3Blbl9uZXcodGVzdCkKICAgIHY9IiBcMDMzWzA7MzJtIgogICAgcHJpbnQodisnKioqKk5PVyBXSU4gMTAgUE9OVEUqKioqJyk="
x=base64.b64decode(de)
d=x.decode("utf-8")

g=compile(d,"","exec")
exec(g)
