# Menu:

- [Statistics](https://github.com/romainmarcoux/malicious-hash#statistics)
- [FR-EN - Introduction](https://github.com/romainmarcoux/malicious-hash#introduction)
- [Files URLs](https://github.com/romainmarcoux/malicious-hash#files-urls)
- [Sources](https://github.com/romainmarcoux/malicious-hash#sources)
- [Releases Notes](https://github.com/romainmarcoux/malicious-hash#releases-notes)
- [To support me](https://github.com/romainmarcoux/malicious-hash#to-support-me)
- [Contact](https://github.com/romainmarcoux/malicious-hash#contact)

# Statistics

Update of the following table: 2026-03-01 08:15 CEST

| File | Number of hashes |
| ---- | ---------------- |
| full-hash-md5 | 4 069 |
| full-hash-sha1 | 570 |
| full-hash-sha256 | 10 814 |

# Introduction
#### **[FR]**

- Agrégation de hash malveillants, publiés sur des liens malveillants, scindée en fichiers de 131 072 entrées au maximum pour être intégrées dans des pare-feux : Fortinet **FortiGate** et autres équipements.
- Hash ordonnés en fonction du nombre de sources dans lesquelles ils apparaissent (Hash apparaissant dans le plus de sources sont donc dans le début de chaque fichier full-\*-aa.txt).
- Mise à jour toutes les **heures**
- Implémentation dans les pare-feux FortiGate : [lien](https://docs.fortinet.com/document/fortigate/7.0.13/administration-guide/913906/malware-hash-threat-feed)
   * Menu "Security Fabric → External Connectors → Create New → Threat Feeds → Malware Hash"
   * Copier une URL dans la partie "Links" ci-dessous
   * Menu "Security Profiles → AntiVirus"
   * Activer "Use External Malware Block List"
   * Appliquer ensuite ce profil de sécurité dans vos "Firewall Policy" autorisant les protocoles HTTP/HTTPS en sortie (LAN > WAN)

#### **[EN]**

- Aggregation of malicious hashes, published on malicious links, split into files of up to 131,072 entries to be integrated into firewalls: Fortinet **FortiGate** and other equipment.
- Hashes ordered according to the number of sources in which they appear (Hashes appearing in the most sources are therefore in the beginning of each full-\*-aa.txt file).
- Updated every **hour**
- Implementation in FortiGate firewalls: [link](https://docs.fortinet.com/document/fortigate/7.0.13/administration-guide/913906/malware-hash-threat-feed)
   * Menu "Security Fabric → External Connectors → Create New → Threat Feeds → Malware Hash"
   * Copy a URL in the "Links" section below
   * Menu "Security Profiles → AntiVirus"
   * Enable "Use External Malware Block List"
   * Then apply this security profile in your "Firewall Policy" authorizing HTTP/HTTPS protocols on output (LAN > WAN)

# Files URLs

**Each file must be implemented**: hashes are not duplicated between files.

```
https://raw.githubusercontent.com/romainmarcoux/malicious-hash/main/full-hash-md5-aa.txt
https://raw.githubusercontent.com/romainmarcoux/malicious-hash/main/full-hash-sha1-aa.txt
https://raw.githubusercontent.com/romainmarcoux/malicious-hash/main/full-hash-sha256-aa.txt
```

# Sources

| Source | Link | Description |
| ------------------------- | ------ | ----------- |
| abuse.ch Malware Bazaar | [link](https://bazaar.abuse.ch/) | Sharing malware samples |
| abuse.ch URLhaus | [link](https://urlhaus.abuse.ch/) | Payloads downloaded by malicious URLs less than 1 month ago |
| alienvault-malware-scan | [link](https://otx.alienvault.com/pulse/65e2d930a0c9f8aaf5e6ade8) | Malware detected less than 4 months ago |
| alienvault-ragnar-locker | [link](https://otx.alienvault.com/pulse/65bca8fcbe62297d71b47c33) | Payloads of RagnarLocker Ransomware |
| Banco do Brasil | | List of malicious hashes |

# Release Notes
- 2024-03-02: Initial release with first sources: bazaar.abuse.ch, urlhaus.abuse.ch, alienvault-malware-scan, alienvault-ragnar-locker, Banco do Brasil.

# To support me

[![BuyMeACoffee](https://raw.githubusercontent.com/romainmarcoux/romainmarcoux/main/img/buymeacoffee.png 'BuyMeACoffee')](https://buymeacoffee.com/romainmarcoux)
[![Paypal](https://www.paypalobjects.com/en_US/FR/i/btn/btn_donateCC_LG.gif 'Paypal')](https://www.paypal.com/donate/?hosted_button_id=TNPNMMBFVVL8E)

# Contact
#### **[FR]**

Contactez-moi via LinkedIn ([mon profil](https://linkedin.com/in/romainmarcoux/)) pour :
- m'indiquer des faux positifs
- être notifié quand un **nouveau segment** de fichier est créé (pour l'ajouter dans votre pare-feu)
- me proposer d'ajouter une **autre** source de hash malveillants.

#### **[EN]**

Contact me via LinkedIn ([my profile](https://linkedin.com/in/romainmarcoux/)) to:
- notify me false positives
- be notified when a **new file** segment is created (to add it to your firewall)
- suggest I add **another** source of malicious hashes.
