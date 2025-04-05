# 💠 Надёжный стейкинг Kusama с ITROCKET: Как подключиться к пулу №213

<img src="https://github.com/mART321/ITstake/blob/main/img/ITR%20redesign.png" alt="stake banner" style="width: 100%; height: 100%; object-fit: cover;" />

## 📚 Содержание

- [🔰 Введение](#введение)
- [🪪 1. Создание кошелька](#1-создание-кошелька)
- [🔌 2. Подключение и проверка минимального стейка](#2-подключение-и-проверка)
- [💸 3. Пополнение кошелька](#3-пополнение-кошелька)
- [🏦 4. Стейк в пул №213](#4-стейк-в-пул-№213)
- [✅ 5. Проверка участия](#5-проверка-участия)
- [🏁 Заключение](#заключение)

---

## 🔰 Введение <a id="введение"></a>

**Kusama** — это масштабируемая и гибкая сеть, связанная с экосистемой Polkadot. Участвуя в стейкинге, вы поддерживаете сеть и получаете пассивный доход.

**ITROCKET** запустили валидаторский пул №213. Гайд поможет вам быстро подключиться и начать зарабатывать.

---
###### 💡 Click ► to open/close image  

### 🪪 1. Создание кошелька <a id="1-создание-кошелька"></a>

<details open>
<summary>1. Установите расширение Polkadot.js Extension</summary>

[Перейти к установке](https://polkadot.js.org/extension/)

<img src="https://github.com/mART321/ITstake/blob/main/img/sait.png" alt="stake banner 1" style="width: 40%; height: 40%; object-fit: cover;" />
<img src="https://github.com/mART321/ITstake/blob/main/img/dwn.png" alt="stake banner 2" style="width: 40%; height: 40%; object-fit: cover;" />
</details>

<details open>
<summary>2. Откройте меню расширений и найдите polkadot{.js}</summary>

Убедитесь, что расширение активно и работает корректно.
</details>

<details open>
<summary>3. Создайте новый аккаунт</summary>

Нажмите на иконку расширения → **+** → **Create new account**

<img src="https://github.com/mART321/ITstake/blob/main/img/c1.png" alt="stake banner 3" style="width: 40%; height: 40%; object-fit: cover;" />
</details>

<details open>
<summary>4. Сохраните seed-фразу</summary>

Это единственный способ восстановить доступ к кошельку. Храните её в надёжном месте!

<img src="https://github.com/mART321/ITstake/blob/main/img/c2.jpeg" alt="stake banner 4" style="width: 40%; height: 40%; object-fit: cover;" />
</details>

<details open>
<summary>5. Завершите создание аккаунта</summary>

Придумайте имя, установите пароль и завершите настройку кошелька.

<img src="https://github.com/mART321/ITstake/blob/main/img/c3.png" alt="stake banner 5" style="width: 40%; height: 40%; object-fit: cover;" />
</details>

<details open>
<summary>6. Убедитесь, что аккаунт создан</summary>

Кошелёк должен отображаться вот так:

<img src="https://github.com/mART321/ITstake/blob/main/img/c4.png" alt="stake banner 6" style="width: 40%; height: 40%; object-fit: cover;" />
</details>

---

## 📉 2. Проверка минимального стейка <a id="2-проверка-минимального-стейка"></a>

1. Откройте [раздел Chain State](https://polkadot.js.org/apps/?rpc=wss://kusama-mainnet-rpc.itrocket.net#/chainstate).

2. В выпадающем списке параметров выберите:
<details open>
<summary>- модуль: `staking`</summary>
<img src="https://github.com/mART321/ITstake/blob/main/img/21.jpeg" style="width: 60%; height: 60%; object-fit: cover;" />
</details>


<details open>
<summary>- метод: `minNominatorBond()`</summary>
<img src="https://github.com/mART321/ITstake/blob/main/img/22.jpeg" style="width: 60%; height: 60%; object-fit: cover;" />
</details>

3. Нажмите кнопку **«+»**, чтобы отобразить текущее значение минимального стейка.
<details open>
<summary>Пример: как выглядит минимальный стейк</summary>
<img src="https://github.com/mART321/ITstake/blob/main/img/23.jpeg" style="width: 60%; height: 60%; object-fit: cover;" />
</details>

Если отображается значение `100000000000`, это эквивалентно **0.1 KSM**. В сети Kusama один KSM состоит из 1 000 000 000 000 планков (Planck) — наименьших единиц. Указанный порог может быть изменён параметрами сети, поэтому его рекомендуется проверять вручную перед началом стейкинга.

---

## 💸 3. Пополнение кошелька <a id="3-пополнение"></a>

Если у вас ещё нет средств на кошельке, пополните его через биржу (например, Bybit, Binance и другие), переведя токены **KSM** на адрес, который вы создали в кошельке Polkadot.js Extension.

Убедитесь, что сумма перевода превышает минимальный порог — **например, 0.2–0.3 KSM**, чтобы с запасом покрыть возможные комиссии и изменения минимального стейка.

---

## 🏦 4. Участие в пуле №213 <a id="4-участие-в-пуле"></a>

1. Перейдите в [раздел Staking → Pools](https://polkadot.js.org/apps/?rpc=wss://kusama-mainnet-rpc.itrocket.net#/staking/pools)

2. Найдите пул с ID **213** — воспользуйтесь встроенным поиском или прокруткой списка.
<details open>
<img src="https://github.com/mART321/ITstake/blob/main/img/3.png" style="width: 50%; height: 50%; object-fit: cover;" />
</details>

3. Нажмите кнопку **Join** или **Stake** напротив пула №213.
<details open>
<img src="https://github.com/mART321/ITstake/blob/main/img/31.png" style="width: 50%; height: 50%; object-fit: cover;" />
</details>

5. Введите сумму токенов для стейкинга. Она должна быть **выше минимального значения**, указанного ранее.
<details open>
<img src="https://github.com/mART321/ITstake/blob/main/img/32.png" style="width: 50%; height: 50%; object-fit: cover;" />
</details>

7. Подтвердите транзакцию через расширение Polkadot.js Extension — появится всплывающее окно для подписи действия.

<details open>
<img src="https://github.com/mART321/ITstake/blob/main/img/33.png" style="width: 50%; height: 50%; object-fit: cover;" />
</details>

<details open>
<img src="https://github.com/mART321/ITstake/blob/main/img/34.png" style="width: 50%; height: 50%; object-fit: cover;" />
</details>
---

## ✅ 5. Проверка участия <a id="5-проверка-участия"></a>

1. Перейдите обратно на вкладку **Pools** и убедитесь, что ваш адрес отображается среди участников пула №213.
<details open>
<img src="https://github.com/mART321/ITstake/blob/main/img/4.png" style="width: 50%; height: 50%; object-fit: cover;" />
</details>

2. Награды начинают поступать через 1–2 эпохи (обычно несколько дней).

---

## 🏁 Заключение <a id="заключение"></a>

Поздравляем! 🎉 Вы успешно застейкали KSM в пуле №213 проекта **ITROCKET**.

Теперь ваши токены работают на вас: приносят доход и поддерживают децентрализацию сети Kusama.

---

[🔝 Вернуться к началу](#📚-содержание)


