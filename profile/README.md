<!-- BEGIN CENTER -->
<div align="center">

<!-- LOGOS --> 
<p>
  <img src="https://github.com/user-attachments/assets/7ec675d4-d52c-4bb5-b5f7-049e33376994"
       alt="WOT-CV Icon"
       width="48" />
</p>
<p>
  <img src="https://github.com/user-attachments/assets/b04a9db9-308e-46ee-be83-5da2387b7d59"
       alt="WOT-CV Logo"
       width="200" />
</p> 
</br>

**[ENGLISH](#english)&nbsp;&nbsp;|&nbsp;&nbsp;[POLSKI](#polski)**

<!-- ─────────────────────────────────────────────────────────────────────────── -->
<!-- ENGLISH VERSION                                                            -->
<!-- ─────────────────────────────────────────────────────────────────────────── -->
<a id="english"></a>

# [WOT-CV](https://wot-cv.com) – Player Recruitment System for [World of Tanks](https://worldoftanks.eu/) Clans

## Table of Contents

</div>
<!-- END CENTER -->

1. [Description](#description)
2. [Key Features](#key-features)
3. [Business Model](#business-model)
4. [Technologies](#technologies)
5. [User Requirements](#user-requirements)
6. [Authors](#authors)
7. [License](#license)

---

<!-- BEGIN CENTER -->
<div align="center">

## Description

[WOT-CV](https://wot-cv.com) is a web application that streamlines the recruitment process
for [World of Tanks](https://worldoftanks.eu/) clans.  
Created as a hobby project by [Daniel Owczarczyk](https://www.linkedin.com/in/daniel-owczarczyk-8b89a6150)
and  [Marek Brajerski](https://www.linkedin.com/in/marek-brajerski), it is designed to simplify a recruiter’s daily
work.

---

## Key Features

</div>
<!-- END CENTER -->

- **Potential-recruit search** – automatically finds players matching clan requirements.
- **Advanced search filters** – configurable criteria based on statistics, activity, or preferred language.
- **Admin panel** – manage clan-member permissions.
- **Check list** – review candidates who meet the chosen criteria.
- **Recruitment statistics** – detailed insights into recruitment effectiveness.
- **Recruitment history** – log of all reviewed players.
- **Auto-invite plugin** – removes the need to send invitations manually.

---

<!-- BEGIN CENTER -->
<div align="center">

## Business Model

| Tier        | Capabilities                      | Limitations                                                               |
|-------------|-----------------------------------|---------------------------------------------------------------------------|
| **Free**    | Core functionality                | • Up to 10 players checked per day<br>• Filters can be changed once a day |
| **Premium** | Unlimited access to every feature | None                                                                      |

---

## Technologies

### Backend

| Technology        | Version / Notes                |
|-------------------|--------------------------------|
| **Java**          | 21                             |
| **Spring Boot**   | 3.4                            |
| **Architecture**  | Hexagonal (Ports & Adapters)   |
| **Threads**       | Virtual threads (Project Loom) |
| **Unit tests**    | Spock Framework                |
| **Service mocks** | WireMock                       |
| **Database**      | MongoDB                        |
| **Migrations**    | Mongock                        |
| **Build tool**    | Maven                          |
| **Log masking**   | Logbook                        |
| **Boilerplate**   | Lombok                         |

### Frontend

| Technology      | Version / Notes                |
|-----------------|--------------------------------|
| **React**       | 19                             |
| **TypeScript**  | 5.x.x                          |
| **UI Kit**      | Material-UI v7                 |
| **State mgmt**  | Redux                          |
| **Bundler**     | Vite                           |
| **Unit tests**  | Vitest & React Testing Library |
| **HTTP mocks**  | MSW (Mock Service Worker)      |
| **Routing**     | React Router                   |
| **Forms**       | Formik                         |
| **i18n**        | i18next                        |
| **Package mgr** | Yarn                           |
| **Linting**     | ESLint                         |

---

## User Requirements

</div>
<!-- END CENTER -->

1. A [Wargaming.net](https://wargaming.net) account.
2. Membership in a [World of Tanks](https://worldoftanks.eu/) clan.
3. One of the following clan roles: **Commander**, **Executive Officer**, **Personnel Officer**, **Combat Officer**, **Intelligence Officer**, **Quartermaster**, **Recruitment Officer**, or **Junior Officer**.

> **Note:** The service never asks for personal data – it relies solely on public data obtained through the
> official [Wargaming.net API](https://developers.wargaming.net/) and [OpenID](https://openid.net/) authentication.

---

<!-- BEGIN CENTER -->
<div align="center">

## Authors

[Daniel Owczarczyk](https://www.linkedin.com/in/daniel-owczarczyk-8b89a6150) & [Marek Brajerski](https://www.linkedin.com/in/marek-brajerski)

---

## License

Hobby project.  
[World of Tanks](https://worldoftanks.eu/) is a trademark of [Wargaming.net](https://wargaming.net).

---

</div>
<!-- END CENTER -->
<!-- BEGIN CENTER -->
<div align="center">

<!-- ─────────────────────────────────────────────────────────────────────────── -->
<!-- WERSJA POLSKA                                                             -->
<!-- ─────────────────────────────────────────────────────────────────────────── -->
<a id="polski"></a>

# [WOT-CV](https://wot-cv.com) – System rekrutacji graczy do klanów [World of Tanks](https://worldoftanks.eu/)

## Spis treści

</div>
<!-- END CENTER -->

1. [Opis](#opis)
2. [Główne funkcjonalności](#główne-funkcjonalności)
3. [Model biznesowy](#model-biznesowy)
4. [Technologie](#technologie)
5. [Wymagania dla użytkowników](#wymagania-dla-użytkowników)
6. [Autorzy](#autorzy)
7. [Licencja](#licencja)

---

<!-- BEGIN CENTER -->
<div align="center">

## Opis

[WOT-CV](https://wot-cv.com) to aplikacja webowa wspierająca proces rekrutacji graczy do klanów w
grze [World of Tanks](https://worldoftanks.eu/).
Projekt powstał jako inicjatywa hobbystyczna
autorów – [Daniela Owczarczyka](https://www.linkedin.com/in/daniel-owczarczyk-8b89a6150)
i [Marka Brajerskiego](https://www.linkedin.com/in/marek-brajerski) – i ma na celu uproszczenie pracy rekruterów
klanowych.

---

## Główne funkcjonalności

</div>
<!-- END CENTER -->

- **Wyszukiwanie potencjalnych rekrutów** – automatyczne odnajdywanie graczy spełniających wymagania klanu.
- **Zaawansowane filtry wyszukiwania** – konfigurowalne kryteria dotyczące statystyk, aktywności czy języka komunikacji.
- **Panel administracyjny** – zarządzanie uprawnieniami członków klanu.
- **Lista graczy do sprawdzenia** – zestawienie kandydatów spełniających określone kryteria.
- **Statystyki rekrutacji** – szczegółowe dane dotyczące skuteczności procesu.
- **Historia rekrutacji** – zapis historii przeanalizowanych graczy.
- **Wtyczka do automatycznego zapraszania** – eliminuje konieczność ręcznego wysyłania zaproszeń.

---

<!-- BEGIN CENTER -->
<div align="center">

## Model biznesowy

| Wariant     | Możliwości                  | Ograniczenia                                                              |
|-------------|-----------------------------|---------------------------------------------------------------------------|
| **Darmowy** | Podstawowa funkcjonalność   | • maks. 10 graczy do sprawdzenia dziennie<br>• zmiana filtrów 1× dziennie |
| **Premium** | Pełny, nielimitowany dostęp | Brak                                                                      |

---

## Technologie

### Backend

| Technologia                   | Wersja / opis                   |
|-------------------------------|---------------------------------|
| **Java**                      | 21                              |
| **Spring Boot**               | 3.4                             |
| **Architektura**              | Heksagonalna (Ports & Adapters) |
| **Wątki**                     | Wirtualne (Project Loom)        |
| **Testy jednostkowe**         | Spock Framework                 |
| **Mockowanie zewn. serwisów** | WireMock                        |
| **Baza danych**               | MongoDB                         |
| **Migracje**                  | Mongock                         |
| **Budowanie**                 | Maven                           |
| **Anonimizacja logów**        | Logbook                         |
| **Boilerplate**               | Lombok                          |

### Frontend

| Technologia               | Wersja / opis                  |
|---------------------------|--------------------------------|
| **React**                 | 19                             |
| **TypeScript**            | 5.x.x                          |
| **UI Kit**                | Material-UI v7                 |
| **Stan aplikacji**        | Redux                          |
| **Bundler**               | Vite                           |
| **Testy jednostkowe**     | Vitest & React Testing Library |
| **Mocki HTTP**            | MSW (Mock Service Worker)      |
| **Routing**               | React Router                   |
| **Formularze**            | Formik                         |
| **Internationalizacja**   | i18next                        |
| **Zarządzanie pakietami** | Yarn                           |
| **Linting**               | ESLint                         |

---

## Wymagania dla użytkowników

</div>
<!-- END CENTER -->

1. Posiadanie konta w domenie [Wargaming.net](https://wargaming.net).
2. Członkostwo w klanie gry [World of Tanks](https://worldoftanks.eu/).
3. Odpowiednia rola w klanie: **Dowódca**, **Oficer Wykonawczy**, **Oficer Kadrowy**, **Oficer Polowy**, **Oficer
   Wywiadu**, **Kwatermistrz**, **Oficer Werbunkowy** lub **Młodszy Oficer**.

> **Uwaga:** Serwis nie wymaga udostępniania danych osobowych – korzysta wyłącznie z publicznych danych uzyskanych
> poprzez oficjalne [Wargaming.net API](https://developers.wargaming.net/) oraz mechanizm [OpenID](https://openid.net/).

---

<!-- BEGIN CENTER -->
<div align="center">

## Autorzy

[Daniel Owczarczyk](https://www.linkedin.com/in/daniel-owczarczyk-8b89a6150) & [Marek Brajerski](https://www.linkedin.com/in/marek-brajerski)

---

## Licencja

Projekt o charakterze hobbystycznym.  
Nazwy i znaki towarowe [World of Tanks](https://worldoftanks.eu/) należą do [Wargaming.net](https://wargaming.net).

---

</div>
<!-- END CENTER -->
