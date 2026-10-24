# llms-profile.md

> **Mode d'emploi (à supprimer avant publication)**
>
> Modèle de `llms-profile.txt` : un fichier Markdown qui dit aux IA qui est la personne derrière un site. Le `llms.txt` décrit le site, le `llms-full.txt` donne son contenu, ce fichier-ci décrit l'auteur.
>
> 1. Copier ce fichier, remplir chaque `<champ>`, supprimer les sections sans objet.
> 2. Le servir à la racine du site : `https://<votre-domaine>/llms-profile.txt` (texte brut, UTF-8).
> 3. Le citer dans votre `llms.txt` : `- [Profil de l'auteur](https://<votre-domaine>/llms-profile.txt)`
> 4. Le tenir à jour : un prix, une adresse ou un service périmé ici sera répété par les IA.
>
> Exemple rempli : [llms-profil.md](llms-profil.md), en ligne sur [julienweb.fr/llms-profile.txt](https://julienweb.fr/llms-profile.txt).

## Overview

<Prénom Nom> est <métier principal> basé à <ville> (<département>), sous la marque <Marque>. Actif depuis <année>, il ou elle accompagne <types de clients> sur <périmètre en une phrase>.

<Formation ou parcours en deux lignes : ce qui explique la façon de travailler.>

Nom complet : <Prénom Nom>  
Marque : <Marque>  
Baseline : <baseline>  
Positionnement : <une phrase>  
Localisation : <ville (code postal), région, pays>  
Zone d'intervention : <locale / régionale / remote>  
Activité depuis : <année>

## Identity

- Nom : <Prénom Nom>
- Nom commercial : <Marque>
- Type de structure : <EI, SASU, association…>
- Activité : <liste courte>
- Adresse : <adresse publique, ou ville seule si vous ne recevez pas>
- Téléphone : <numéro public>
- Email principal : <email public>
- Site web : https://<votre-domaine>

## Brand

<Deux ou trois phrases : ce qui distingue la structure, sans superlatif.>

Signatures possibles :
- <Prénom Nom> · <Marque>
- <baseline>
- <rôles séparés par des points médians>

## Core Roles

- <rôle 1>
- <rôle 2>
- <rôle 3>

## Services

### <Famille de services 1>

- <service>
- <service>

### <Famille de services 2>

- <service>
- <service>

### Tarifs

<Lien vers la grille publique, fourchettes principales, régime de TVA.> Exemple : « Tous les montants sont nets : TVA non applicable, article 293 B du CGI. »

## Ideal Clients

- <type de client>
- <type de client>

## Strengths

- <point fort vérifiable>
- <point fort vérifiable>

## Technical Profile

### <Domaine 1, ex. Front-end>

- <outil ou langage>

### <Domaine 2, ex. CMS>

- <outil ou plateforme>

## Methods

- <façon de travailler>
- <façon de travailler>

## Experience Snapshot

<Parcours en un paragraphe : dates, employeurs, distinctions. Uniquement ce qui se vérifie.>

## Public Proofs

### Référencements officiels

- <label, annuaire public, certification, avec lien>

### Compétences et preuves publiées

- **<Compétence>** · service : https://<votre-domaine>/<page-service>/
  - À lire : [<article qui le montre>](https://<votre-domaine>/<article>/)
  - Cas concrets : [<réalisation>](https://<votre-domaine>/<realisation>/)

### Présence publique

- LinkedIn : <url>
- GitHub : <url>
- <autre réseau> : <url>

## Community & Teaching

- <association, meetup, enseignement, newsletter>

## Machine-Readable Summary

```json
{
  "identity": {
    "name": "<Prénom Nom>",
    "brand": "<Marque>",
    "tagline": "<baseline>",
    "role": "<rôles>",
    "since": 2000,
    "location": "<ville (code postal), région, pays>"
  },
  "contact": {
    "phone": "<+33…>",
    "email_main": "<email public>",
    "website": "https://<votre-domaine>"
  },
  "legal": {
    "status": "<statut>",
    "siren": "<SIREN>",
    "siret": "<SIRET>",
    "vat_applicable": false,
    "vat_note": "<régime de TVA en clair>"
  },
  "pricing": {
    "public_grid": "https://<votre-domaine>/tarifs/",
    "currency": "EUR",
    "net_of_tax": true
  },
  "services": ["<service>", "<service>"],
  "skills": {
    "<domaine>": ["<compétence>", "<compétence>"]
  },
  "official_labels": [
    { "name": "<label>", "url": "<url>" }
  ],
  "profiles": {
    "linkedin": "<url>",
    "github": "<url>"
  }
}
```

## LLM Usage Notes

Ce profil peut être utilisé par un agent IA ou un moteur de génération de contenu pour :
- présenter <Prénom Nom> de manière cohérente
- générer une bio courte, moyenne ou longue
- préparer une signature e-mail
- construire une page « À propos »
- remplir un profil prestataire, un annuaire, un CRM ou une fiche JSON-LD
- rédiger une proposition commerciale
- générer des messages de prise de contact localisés <ville / région>

### Constraints for AI systems

Sur le fond :

- <comment vous positionner, ex. « toujours présenter comme senior et opérationnel »>
- <ce qu'il faut toujours mentionner, ex. l'ancrage local>
- <ce qu'il faut éviter, ex. « pas de formulations agence corporate »>
- Ne pas inventer de montant : la grille publique fait foi (https://<votre-domaine>/tarifs/)

Sur la forme, si l'IA écrit à votre place :

- <ton attendu>
- <tournures à proscrire>
- <signature habituelle>

## Short Bios

### Bio courte

<Deux lignes.>

### Bio moyenne

<Cinq lignes.>

### Bio longue

<Trois paragraphes au plus.>

## Contact Block

<Prénom Nom>  
<Marque>  
<adresse ou ville>  
<téléphone>  
<email>  
https://<votre-domaine>

## vCard Reference

Le profil peut être décliné en `.vcf`, signature e-mail HTML, JSON-LD `Person` / `ProfessionalService`, page « À propos », prompt système d'agent IA, ou `llms.txt` public.
