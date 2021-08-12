{% warning %}

**Nota:** El Registro de Docker del {% data variables.product.prodname_registry %} {% if enterpriseServerVersions contains currentVersion or currentVersion == "github-ae@latest" %} se suspenderá en un lanzamiento subsecuente de {% data variables.product.product_name %} por el {% data variables.product.prodname_container_registry %}, el cual ofrece compatibilidad de contenedores mejorada.{% elsif currentVersion == "free-pro-team@latest" %} se sustituirá con el {% data variables.product.prodname_container_registry %}, el cual ofrece una compatibilidad mejorada para los contenedores. {% endif %} {% if currentVersion == "free-pro-team@latest" %} Para aprender cómo migrar tus imágenes de Docker y cualquier flujo de trabajo que los utilice, consulta la sección "[Migrarse al {% data variables.product.prodname_container_registry %} desde el registro de Docker](/packages/working-with-a-github-packages-registry/migrating-to-the-container-registry-from-the-docker-registry)". {% endif %}

{% endwarning %}