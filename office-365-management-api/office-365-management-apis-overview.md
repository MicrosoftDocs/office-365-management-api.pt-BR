---
ms.technology: o365-service-communications
ms.TocTitle: Office 365 Management APIs overview
title: Visão geral das APIs de Gerenciamento do Office 365
description: Oferecem uma plataforma de extensibilidade única para todas as tarefas de gerenciamento de clientes e de parceiros do Office 365, incluindo comunicações do serviço, segurança, conformidade, relatórios e auditoria.
ms.ContentId: 4fca85f9-efa6-3b4b-b10d-a07cb31f803f
ms.topic: reference (API)
ms.date: 09/28/2016
localization_priority: Priority
ms.openlocfilehash: 4f0e9414b1f2691f43a8b79e92e39bc589beeb89
ms.sourcegitcommit: ec60dbd5990cfc61b8c000b423e7ade25fa613a8
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/09/2020
ms.locfileid: "48397458"
---
# <a name="office-365-management-apis-overview"></a>Visão geral das APIs de Gerenciamento do Office 365

As APIs de Gerenciamento do Office 365 oferecem uma plataforma de extensibilidade única para todas as tarefas de gerenciamento de clientes e de parceiros do Office 365, incluindo comunicações de serviço, segurança, conformidade, relatórios e auditoria. Todas as APIs de Gerenciamento do Office 365 são consistentes no design e na implementação com o pacote atual de APIs REST do Office 365, usando abordagens comuns de padrões da indústria, incluindo OAuth v2, OData v4 e JSON. Como em outras APIs do Office 365, os aplicativos são registrados no Azure Active Directory, oferecendo aos desenvolvedores uma forma consistente de autenticar e autorizar os aplicativos.

Publique suas dúvidas sobre as APIs de Gerenciamento do Office 365 no [Stack Overflow](http://stackoverflow.com/tags/office365) usando a tag [office365].

## <a name="office-365-service-communications-api-preview"></a>API de Comunicações do Serviço do Office 365 (versão prévia)

A API de Comunicações do Serviço do Office 365 foi lançada no modo de visualização. Ela substitui a API de Comunicações do Serviço do Office 365 para fornecer informações sobre a integridade do serviço para parceiros e administradores de locatários. Ao contrário da versão anterior, a nova API de Comunicações do Serviço fornece uma experiência coesa na plataforma, com as APIs REST criadas de forma consistentemente, incluindo a nomenclatura da URL, o formato de dados e a autenticação.

Os novos recursos são adicionados somente para a nova versão da API, incentivando a adoção antecipada por clientes herdados. Quando o Anúncio Geral da API de Comunicações do Serviço do Office 365 foi feito, a versão anterior da API de Comunicações do Serviço iniciou um período de substituição. 

Confira a referência de operações em [Referência da API de Comunicações do Serviço do Office 365 (versão prévia)](office-365-service-communications-api-reference.md).


## <a name="office-365-management-activity-api"></a>API da Atividade de Gerenciamento do Office 365

A API da Atividade de Gerenciamento do Office 365 fornece informações sobre várias ações e eventos de usuário, administração, sistema e políticas dos logs de atividades do Office 365 e do Azure Active Directory. Clientes e parceiros podem usar essa informação para aprimorar ou criar novas soluções de monitoramento de conformidade, segurança e operações para empresas. 

Confira referências de operações em [Referência da API da Atividade de Gerenciamento do Office 365](office-365-management-activity-api-reference.md).

## <a name="see-also"></a>Confira também

- [Introdução às APIs de Gerenciamento do Office 365](get-started-with-office-365-management-apis.md)
- [Esquema da API da Atividade de Gerenciamento do Office 365](office-365-management-activity-api-schema.md)
- [Solução de problemas da API da Atividade de Gerenciamento do Office 365](troubleshooting-the-office-365-management-activity-api.md)
- [APIs REST do Office 365](https://docs.microsoft.com/previous-versions/office/office-365-api/how-to/platform-development-overview)

