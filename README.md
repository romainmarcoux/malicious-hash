Update of the following table: 2026-05-17 01:13 CEST

| File | Number of hashes |
| ---- | ---------------- |
| full-hash-md5 | 4 082 |
| full-hash-sha1 | 600 |
| full-hash-sha256 | 73 317 |

<details>
  <summary><b>🇫🇷 Introduction</b></summary>
  <p>

- Agrégation de hash malveillants, publiés sur des liens malveillants, scindée en fichiers de 131 072 entrées au maximum pour être intégrées dans des pare-feux : Fortinet **FortiGate** et autres équipements.
- Hash ordonnés en fonction du nombre de sources dans lesquelles ils apparaissent (Hash apparaissant dans le plus de sources sont donc dans le début de chaque fichier full-\*-aa.txt).
- Mise à jour toutes les **heures** ⏱️
- Implémentation dans les pare-feux FortiGate : [lien](https://docs.fortinet.com/document/fortigate/7.0.13/administration-guide/913906/malware-hash-threat-feed)
   * Menu "Security Fabric → External Connectors → Create New → Threat Feeds → Malware Hash"
   * Copier une URL dans la partie "Links" ci-dessous
   * Menu "Security Profiles → AntiVirus"
   * Activer "Use External Malware Block List"
   * Appliquer ensuite ce profil de sécurité dans vos "Firewall Policy" autorisant les protocoles HTTP/HTTPS en sortie (LAN > WAN)

</p>
</details>
<details>
  <summary><b>🇬🇧 Introduction</b></summary>
  <p>

- Aggregation of malicious hashes, published on malicious links, split into files of up to 131,072 entries to be integrated into firewalls: Fortinet **FortiGate** and other equipment.
- Hashes ordered according to the number of sources in which they appear (Hashes appearing in the most sources are therefore in the beginning of each full-\*-aa.txt file).
- Updated every **hour** ⏱️
- Implementation in FortiGate firewalls: [link](https://docs.fortinet.com/document/fortigate/7.0.13/administration-guide/913906/malware-hash-threat-feed)
   * Menu "Security Fabric → External Connectors → Create New → Threat Feeds → Malware Hash"
   * Copy a URL in the "Links" section below
   * Menu "Security Profiles → AntiVirus"
   * Enable "Use External Malware Block List"
   * Then apply this security profile in your "Firewall Policy" authorizing HTTP/HTTPS protocols on output (LAN > WAN)

</p>
</details>
<details>
  <summary><b>🔗 URL of files to copy paste ⧉</b></summary>
  <p>

**Each file must be implemented**: hashes are not duplicated between files.

```
https://raw.githubusercontent.com/romainmarcoux/malicious-hash/main/full-hash-md5-aa.txt
```
```
https://raw.githubusercontent.com/romainmarcoux/malicious-hash/main/full-hash-sha1-aa.txt
```
```
https://raw.githubusercontent.com/romainmarcoux/malicious-hash/main/full-hash-sha256-aa.txt
```

</p>
</details>
<details>
  <summary><b>Sources</b></summary>
  <p>

| Source | Link | Description |
| ------------------------- | ------ | ----------- |
| abuse.ch Malware Bazaar | [link](https://bazaar.abuse.ch/) | Sharing malware samples |
| abuse.ch URLhaus | [link](https://urlhaus.abuse.ch/) | Payloads downloaded by malicious URLs less than 1 month ago |
| alienvault-malware-scan | [link](https://otx.alienvault.com/pulse/65e2d930a0c9f8aaf5e6ade8) | Malware detected less than 4 months ago |
| alienvault-ragnar-locker | [link](https://otx.alienvault.com/pulse/65bca8fcbe62297d71b47c33) | Payloads of RagnarLocker Ransomware |
| Banco do Brasil | | List of malicious hashes |

</p>
</details>
<details>
  <summary><b>Release Notes 📋</b></summary>
  <p>

- 2024-03-02: Initial release with first sources: bazaar.abuse.ch, urlhaus.abuse.ch, alienvault-malware-scan, alienvault-ragnar-locker, Banco do Brasil.

</p>
</details>
<details>
  <summary><b>🇫🇷 Qui suis-je ?</b></summary>
  <p>

Je suis expert freelance en cybersécurité, notamment sur les pare-feux.

Je maintiens ce projet depuis 2023 pour aider la communauté à se protéger contre les cybermenaces.

N'hésitez pas à me consulter pour vos besoins d'expertise pare-feux (audit, intégration, migration, problématiques ...) : voir contact ci-dessous.

</p>
</details>
<details>
  <summary><b>🇬🇧 Who am I?</b></summary>
  <p>

I am a freelance cybersecurity expert, particularly on firewalls.

I have been maintaining this project since 2023 to help the community protect itself against cyber threats.

Do not hesitate to consult me for your firewall expertise needs (audit, integration, migration, issues, etc.): see contact below.

</p>
</details>
<details>
  <summary><b>To support me 🫴</b></summary>
  <p>

[![BuyMeACoffee](https://raw.githubusercontent.com/romainmarcoux/romainmarcoux/main/img/buymeacoffee.png 'BuyMeACoffee')](https://buymeacoffee.com/romainmarcoux)
[![Paypal](https://www.paypalobjects.com/en_US/FR/i/btn/btn_donateCC_LG.gif 'Paypal')](https://www.paypal.com/donate/?hosted_button_id=TNPNMMBFVVL8E)

</p>
</details>
<details>
  <summary><b>🇫🇷 📬 Pour me contacter (faux positifs, idées, remerciements ...)</b></summary>
  <p>

Contactez-moi via LinkedIn ([mon profil](https://linkedin.com/in/romainmarcoux/)) pour :
- m'indiquer des faux positifs
- me proposer d'ajouter une **autre** source de hash malveillants (voir section "Sources" ci-dessus)
- me solliciter pour vos besoins d'expertise pare-feux (audit, intégration, migration, problématiques ...)
- me remercier et m'encourager pour le maintien de ce projet 😉

</p>
</details>
<details>
  <summary><b>🇬🇧 📬 To contact me (false positives, ideas, thanks, etc.)</b></summary>
  <p>

Contact me via LinkedIn ([my profile](https://linkedin.com/in/romainmarcoux/)) to:
- notify me false positives
- suggest I add **another** source of malicious hashes (see "Sources" section above)
- to consult me for your firewall expertise needs (audit, integration, migration, issues, etc.)
- thank me and encourage me for maintaining this project 😉

</p>
</details>

