---
ms.openlocfilehash: 8acbacc0b39b108fdd05473ceb85e65bfe0e92d0
ms.sourcegitcommit: fb047f9450b41b24afc43d9512a5db2a2b750a2a
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/11/2022
ms.locfileid: "145117016"
---
Настройка заданий для запуска в контейнере упрощает сетевые конфигурации между заданием и контейнерами служб. Контейнеры Docker в одной пользовательской сети моста предоставляют все порты друг другу, поэтому вам не нужно сопоставлять порты контейнера службы с узлом Docker. Вы можете получить доступ к контейнеру службы из контейнера заданий с помощью метки, настроенной в рабочем процессе.