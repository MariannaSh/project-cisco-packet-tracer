## Projekt Sieciowy - Konfiguracja i Implementacja

### Opis Projektu

**Cel projektu:** Celem projektu było skonfigurowanie kompleksowej sieci lokalnej z wykorzystaniem technologii VLAN, protokołu RIP v2 oraz usług DHCP, VoIP, VPN, SSH i NetFlow.

### Zadania i Wykonane Prace

#### Zadanie 1: Konfiguracja Sieci VLAN i Routing RIP v2
- **Utworzenie Sieci:** Zbudowano sieć złożoną z dwóch routerów oraz dwóch przełączników.
- **Routing RIP v2:** Skonfigurowano routing dynamiczny z wykorzystaniem protokołu RIP v2 na obu routerach.
- **VLAN-y:** Utworzono cztery VLAN-y:
  - VLAN 10: VOIP
  - VLAN 20: nauczyciele
  - VLAN 30: uczniowie
  - VLAN 40: administracja
- **Przypisanie Interfejsów:** Przypisano odpowiednie interfejsy do każdego VLAN-u, np. PC dla uczniów podłączono do portu fa0/10.
- **Adresacja DHCP:** Skonfigurowano serwer DHCP dla każdego VLAN-u, np. VLAN 10: 192.168.1.0/24, VLAN 20: 192.168.2.0/24.
- **Konfiguracja Trunk:** Skonfigurowano połączenie trunkowe między sw1 a sw2.

#### Zadanie 2: Konfiguracja Centralki Telefonicznej 
- **Oddział I:** Skonfigurowano trzy aparaty telefoniczne z numeracją trzycyfrową (np. 112, 134, 156).
- **Oddział II:** Skonfigurowano dwa aparaty telefoniczne z numeracją dwucyfrową (numery dowolne).
- **Łączność Między Oddziałami:** Umożliwiono wzajemne połączenia telefoniczne między aparatami z obu oddziałów.

#### Zadanie 3: Konfiguracja Serwera VPN 
- **Oddział II:** Utworzono i skonfigurowano serwer VPN, umożliwiający bezpieczne połączenia zdalne do sieci lokalnej.

#### Zadanie 4: Konfiguracja SSH na przełączniku sw1 
- **SSH:** Skonfigurowano protokół SSH na przełączniku sw1 w celu zapewnienia bezpiecznego zdalnego dostępu do urządzenia.

#### Zadanie 5: Konfiguracja NetFlow Collector na Laptopie Informatyka 2 
- **NetFlow:** Skonfigurowano NetFlow collector na laptopie Informatyka 2 do monitorowania ruchu sieciowego.

### Podsumowanie

Projekt obejmował zaawansowane zadania sieciowe, w tym konfigurację VLAN-ów, routingu RIP v2, DHCP, centralek telefonicznych, serwera VPN, SSH oraz NetFlow. Każde z zadań zostało pomyślnie zrealizowane, zapewniając wydajną i bezpieczną sieć lokalną.
