{% data variables.product.company_short %} cobra por la {% data variables.product.prodname_advanced_security %} por cada confirmante. {% if currentVersion == "free-pro-team@latest" %}Para obtener más información, consulta la sección "[Administrar el licenciamiento de la {% data variables.product.prodname_GH_advanced_security %}](/billing/managing-licensing-for-github-advanced-security)."{% elsif currentVersion ver_gt "enterprise-server@3.0" %}Para obtener más información, consulta la sección "[Administrar la {% data variables.product.prodname_GH_advanced_security %} para tu empresa](/admin/advanced-security)".{% endif %}

Puedes requerir una política que controle si se les permite a los administradores de repositorio habilitar características para {% data variables.product.prodname_advanced_security %} en los repositorios de una organización. Puedes configurar una política para todas las organizaciones que le pertenezcan a tu cuenta empresarial o para las organizaciones individuales que elijas.

El dejar de permitir la {% data variables.product.prodname_advanced_security %} para una organización previene que los administradores de repositorio habiliten las características de la {% data variables.product.prodname_advanced_security %} para los repositorios adicionales, pero no inhabilita las características para los repositorios en donde estas ya se hayan habilitado. Para obtener más información acerca de la configuración de las características de {% data variables.product.prodname_advanced_security %}, consulta la sección "[Administrar la configuración de análisis y seguridad para tu organización](/organizations/keeping-your-organization-secure/managing-security-and-analysis-settings-for-your-organization)" o "[Administrar la configuración de análisis y seguridad para tu repositorio](/github/administering-a-repository/managing-security-and-analysis-settings-for-your-repository)".