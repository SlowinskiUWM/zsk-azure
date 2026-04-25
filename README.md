Azure AD Lab (ZSK)
Deploy środowiska

Kliknij:

https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/SlowinskiUWM/zsk-azure/main/template.json

Szablon:

2 maszyny wirtualne (dc1-zsk, client1-zsk)

sieć VNet

adresy IP

NSG

dyski

Po wdrożeniu:

Połącz się z dc1-zsk

Zainstaluj Active Directory

Utwórz domenę zsk.local

Dołącz client1-zsk do domeny

Koszty:

Po zajęciach usuń całą grupę zasobów:

Resource Group → Delete

Uwaga

Szablon NIE konfiguruje Active Directory automatycznie.
To trzeba zrobić ręcznie




https://raw.githubusercontent.com/SlowinskiUWM/zsk-azure/refs/heads/main/template.json
