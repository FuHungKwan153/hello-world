ssh-keygen -t rsa -b 4096 -C "hkfu@wiseally.com.hk"

ssh-keygen -t rsa -b 4096 -C "FuHungKwan153@github.com"

eval $(ssh-agent -s)

ssh-add ~/.ssh/hkfu3

clip < ~/.ssh/hkfu3.pub

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQD+cJOVrs3HqNOqgAPnesRIFeCELt6j8PYS3Hl22flkWe1ufAkAtoWeicd2ETPdftng/XZe3CW1afx8zsUoB+qzH07LZL5CBBebZ6mATwhrgn2VI8zv03JwYq8BWz38MB1NJroTkQ3hgJLIguEZURyVlz6qhGQpg5BhM3+lQ1esMgaPo/3Zug1+kjafmi5cTm6BIV79dsmLezKC8DzdoGLvamMLgx0wqp1f0guyMdLmmj3Mm3TuAwfW3Qoz//a5Zi+7hg7ETwwwmGuJBvXPHzJm3U0O+Bdpav4ABRuJtqmVcydImDgLkLmnNTBefceSSyLj8vbj3b9XsNL2Kx/n73NgJKMBJFxXr96aiQdObike98BGyGoRgv7Fymci0YE5Q8FZjIgJWb/ihM4lb2Bp4XGrhlAAezsLKN1fxCafPVAEYcNIfdHjJeNq270cXiSDx/6ptv8B7fPlmqwPFc5bgO+vd0Lhx8ZORshSe2baxSX1U3cdToe8I7wbawSfs24oD/V1v0EjIzd8sHYpDfH0g8cB1eN1z5bPu7Z0oiXXO7F4ybKK5uywyv10VFvw7Oa8lztJPL/ubD1oI+WMVCbb5bFH/aoQ/yC3T2dGoNTVNhiG+MYRZmtNbX7xmKvmTwA5Ey5YNOOss9adj25H1rHLtPiaSsy67p4kKtx5flAHsI4aDQ== FuHungKwan153@github.com

git clone git@github.com:FuHungKwan153/hello-world.git
