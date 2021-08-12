If someone checks a secret with a known pattern into a {% if currentVersion == "free-pro-team@latest" %}public or private{% endif %} repository on {% data variables.product.product_name %}, {% data variables.product.prodname_secret_scanning %} catches the secret as it's checked in, and helps you mitigate the impact of the leak. Os administradores do repositório são notificados sobre qualquer submissão que contém um segredo e podem visualizar rapidamente todos os segredos detectados na aba Segurança do repositório.