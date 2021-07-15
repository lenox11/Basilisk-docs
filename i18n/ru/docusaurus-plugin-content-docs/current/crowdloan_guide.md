---
id: crowdloan_guide
title: Участвуйте в Crowdloan
---

import useBaseUrl from '@docusaurus/useBaseUrl';

Эта статья проведет вас через процесс участия в [Crowdloan Basilisk](/basilisk_crowdloan) с помощью специальной страницы Crowdloan: https://loan.bsx.fi

## Требования {#requirements}

Чтобы участвовать с использованием специальной страницы Crowdloan, у вас должен быть кошелек [Polkadot.js](https://polkadot.js.org/extension/) с токенами KSM, которые вы хотите положить в стейк.

:::предупреждение

Участвовать в Crowdloan с помощью аппаратного кошелька невозможно. В настоящее время аппаратные кошельки не поддерживают модуль Cusama Crowdloan.

:::

## 00 Пользовательский интерфейс Crowdloan {#00-crowdloan-ui}

Чтобы получить доступ к пользовательскому интерфейсу Basilisk Crowdloan, перейдите по адресу https://loan.bsx.fi.

<div style={{textAlign: 'center', marginBottom: '2rem'}}>
  <img alt="create-account" src={useBaseUrl('/img/crowdloan-guide/chart.png')}  />
</div>

На диаграмме посередине представлена информация о текущем аукционе по слоту парачейна. Зеленая линия показывает количество токенов KSM, поднятых Basilisk, а желтая линия соответствует KSM, поднятому основным конкурентом Basilisk. Горизонтальная красная линия обозначает начало периода закрытия целевого аукциона парачейна. Вся эта информация важна для определения суммы [наград BSX и бонусов HDX](/basilisk_crowdloan), которые вы получите за свой вклад.


## 01 Выберите свой адрес {#01-select-address}


Для начала нажмите *изменить свою учетную запись (change your account)* и выберите адрес, на котором находятся ваши токены KSM.

<div style={{textAlign: 'center', marginBottom: '2rem'}}>
  <img alt="create-account" src={useBaseUrl('/img/crowdloan-guide/select-account.png')}  />
</div>

## 02 Введите свой взнос в KSM {#02-enter-ksm-contribution}

На следующем шаге вы можете ввести сумму KSM, которую хотите внести. После этого вы увидите прогноз вознаграждений, которые вы собираетесь получить:

* **Minimum BSX Received** - минимальное количество токенов BSX, которое вы можете рассчитывать получить за свой вклад. Точная сумма может быть определена только после закрытия Crowdloan в случае успешного проведения аукциона.

* ** Current BSX Received ** - **дикая** оценка того, сколько вы получите в текущих условиях аукциона. Эта оценка может быть недостоверной.

* **Current HDX Received** - размер бонуса HDX, который будет получен за вклад.

Если вы хотите узнать больше о механике расчета наград, обратитесь к [записи о краудзайме Basilisk](/basilisk_crowdloan).

## 03 Отправьте свой вклад {#03-submit}

Чтобы завершить процесс, нажмите *Contribute* и подпишите транзакцию, используя учетную запись, в которой хранятся ваши токены KSM.

<div style={{textAlign: 'center', marginBottom: '2rem'}}>
  <img alt="create-account" src={useBaseUrl('/img/crowdloan-guide/sign-submit.png')}  />
</div>
