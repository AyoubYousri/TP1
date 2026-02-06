<img width="659" height="644" alt="Capture d&#39;écran 2026-02-06 120217" src="https://github.com/user-attachments/assets/fc8d9e09-e130-4a73-85ec-87638811dab3" />
J'ai d'abord importé la machine virtuelle Mobexler dans VMware en définissant son nom et son emplacement de stockage.

<img width="2371" height="1459" alt="Capture d&#39;écran 2026-02-06 120758" src="https://github.com/user-attachments/assets/b05e3d4e-9b9a-47d4-b6d1-97c1b9269ef5" />
Une fois la VM créée, j'ai vérifié ses ressources (4 Go de RAM, 2 CPU) et noté les identifiants par défaut (mobexler).

<img width="1888" height="1112" alt="Capture d&#39;écran 2026-02-06 130753" src="https://github.com/user-attachments/assets/76a2f64c-f7d5-477f-ad13-4fb473e24758" />
J'ai démarré le système et réussi à me connecter au bureau après avoir saisi le mot de passe.

<img width="1097" height="842" alt="Capture d&#39;écran 2026-02-06 131122" src="https://github.com/user-attachments/assets/a98ac1c2-4ebf-4a11-87b5-7273e95bf458" />
<img width="993" height="320" alt="Capture d&#39;écran 2026-02-06 131141" src="https://github.com/user-attachments/assets/67eb5c91-022e-4afd-b31a-73d6d44dd6a2" />
Via le terminal, j'ai confirmé que ma configuration réseau fonctionne avec la commande ip a et un ping réussi sur Internet (8.8.8.8).

<img width="664" height="448" alt="Capture d&#39;écran 2026-02-06 131254" src="https://github.com/user-attachments/assets/5bfc278e-7e98-4e8c-a020-829b9fee3342" />
Pour plus de sécurité, j'ai créé un snapshot (point de restauration) nommé CLEAN_BASELINE_TP1 pour figer cet état fonctionnel.

<img width="708" height="318" alt="Capture d&#39;écran 2026-02-06 131437" src="https://github.com/user-attachments/assets/8f47a914-771f-4c9a-92c2-4ee5c249a7db" />
Enfin, j'ai testé adb pour m'assurer que les outils de diagnostic mobile sont bien installés et prêts.





