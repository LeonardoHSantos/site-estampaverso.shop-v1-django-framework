# blog-noticias-django-framework
### Projeto pessoal de desenvolvimento de um Blog de notícias usando Django Framework, MySQL, HTML, CSS, JavaScript, AWS e Oracle.

### #Permitindo o usuário Linux ($USER) a instalar as dependências do projeto

Durante os primeiros Deploys do site no Ubuntu, me deparei com problemas de permissão para instalar as dependências "requirements.txt".

#### Se você se deparar com este problema, tente executar esse comando:<br>
<pre>
<code>
sudo chown -R $USER:$USER /home/ubuntu/blog_fatos_e_dados/blog-noticias-django-framework/venv/
</code>
</pre>
