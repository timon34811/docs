---
title: Gerenciando seu limite de gastos para o GitHub Actions (Ações do GitHub)
intro: 'Você pode definir um limite de gastos para o uso do {% data variables.product.prodname_actions %}.'
product: '{% data reusables.gated-features.actions %}'
versions:
  free-pro-team: '*'
---

### Sobre sintaxe limites de gastos para o {% data variables.product.prodname_actions %}

{% data reusables.github-actions.actions-billing %}

{% data reusables.github-actions.actions-spending-limit-brief %}

{% data reusables.actions.actions-packages-set-spending-limit %} For more information about pricing for {% data variables.product.prodname_actions %} usage, see "[About billing for {% data variables.product.prodname_actions %}](/github/setting-up-and-managing-billing-and-payments-on-github/about-billing-for-github-actions)."

As soon as you set a spending limit other than $0, you will be responsible for any existing overages in the current billing period. Por exemplo, se a sua organização usa o {% data variables.product.prodname_team %}, não permite excessos, e cria artefatos de fluxo de trabalho que aumentam seu uso de armazenamento para o mês de 1.9GB para 2.1GB, você usará um pouco mais de armazenamento do que os 2GB que seu produto inclui.

Because you have not enabled overages, your next attempt to create a workflow artifact will fail. Você não receberá uma fatura pelo excesso de 0.1GB naquele mês. However, if you enable overages, your first bill will include the 0.1GB of existing overage for the current billing cycle, as well as any additional overages you accrue.

### Gerenciando o limite de gastos de {% data variables.product.prodname_actions %} para sua conta de usuário

Qualquer pessoa pode gerenciar o limite de gastos do {% data variables.product.prodname_actions %} para sua própria conta de usuário.

{% data reusables.user_settings.access_settings %}
{% data reusables.user_settings.billing %}
{% data reusables.user_settings.cost-management-tab %}
{% data reusables.dotcom_billing.monthly-spending-limit %}
{% data reusables.dotcom_billing.update-spending-limit %}

### Gerenciando o limite de gastos de {% data variables.product.prodname_actions %} para sua organização

Proprietários de organizações e gestores de faturamento podem gerenciar o limite de gastos de {% data variables.product.prodname_actions %} para uma organização.

{% data reusables.profile.access_profile %}
{% data reusables.profile.access_org %}
{% data reusables.organizations.org_settings %}
{% data reusables.organizations.billing %}
{% data reusables.user_settings.cost-management-tab %}
{% data reusables.dotcom_billing.monthly-spending-limit %}
{% data reusables.dotcom_billing.update-spending-limit %}

### Gerenciando o limite de gastos de {% data variables.product.prodname_actions %} para sua conta corporativa

Proprietários de organizações e gestores de faturamento podem gerenciar o limite de gastos de {% data variables.product.prodname_actions %} para uma conta corporativa.

{% data reusables.enterprise-accounts.access-enterprise %}
{% data reusables.enterprise-accounts.settings-tab %}
{% data reusables.enterprise-accounts.billing-tab %}
1. Em "
{% data variables.product.prodname_actions %} e pacotes de uso mensal", clique em **Gestão de custo**.
  ![Aba de gestão de custos](/assets/images/help/settings/cost-management-tab-enterprise.png)
{% data reusables.dotcom_billing.monthly-spending-limit %}
{% data reusables.dotcom_billing.update-spending-limit %}
