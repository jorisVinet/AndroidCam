# Projet Android Studio - Application de capture et d'envoi d'images

Ce projet Android Studio a pour objectif de créer une application permettant de capturer des images à partir de la caméra du téléphone, de les encoder, puis de les envoyer via TCP/IP. Le développement de cette application a nécessité l'utilisation de C++ en plus du langage Java utilisé dans Android Studio.

## Fonctionnalités Principales

- **Capture d'Images**: L'application peut accéder aux caméras du téléphone pour capturer des images en direct.
- **Encodage d'Images**: Les images capturées sont encodées pour réduire leur taille et faciliter leur transmission.
- **Transmission via TCP/IP**: Les images encodées sont envoyées à un serveur distant via une connexion TCP/IP.

## Collaborations et Extensions

Pour les fonctionnalités développées en plus, nous avons collaboré avec le groupe de Basile et William afin de produire un seul code amélioré implémentant des fonctions de traitement d'images. Les fonctionnalités ajoutées incluent :

- **Inversion des Couleurs**: Permet d'inverser les couleurs d'une image.
- **Détection des Bords d'une Image**: Identifie les bords d'une image en la rendant verte.
- **Zoom**: Permet de zoomer sur une partie spécifique de l'image.
- **Flou**: Applique un effet de flou à l'image.

## Étapes du développement

1. **Capture d'image et envoi via TCP/IP**: Nous avons commencé par mettre en place la capture d'images à partir de la caméra du téléphone et leur envoi via TCP/IP. Cette étape nous a permis de mettre en place les bases de l'application.

2. **Tests de l'envoi de flux vidéo via RTSP**: Nous avons ensuite tenté de mettre en œuvre l'envoi de flux vidéo via RTSP. Malheureusement, cette approche n'a pas abouti après des tests approfondis.

3. **Collaboration avec le groupe de Basile et William pour de nouvelles fonctionnalités**: Face à l'impasse rencontrée avec l'envoi de flux vidéo via RTSP, nous avons décidé de collaborer avec le groupe de Basile et William pour développer de nouvelles fonctionnalités. Ainsi, nous avons intégré à notre application des fonctions de traitement d'images, notamment l'inversion des couleurs, la détection des bords, le zoom et le flou. Cette collaboration nous a permis de produire un code amélioré et complet, répondant aux besoins de l'application.
