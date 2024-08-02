![image](https://github.com/user-attachments/assets/e1af8764-a40b-417f-b4e9-b523d8d0898b)

## Let's Defend
>LetsDefend ajuda você a construir uma carreira na equipe azul com experiência prática, investigando ataques cibernéticos reais dentro de um SOC simulado.

## SOC138 - Detected Suspicious Xls File
![Captura de Tela 2024-08-02 às 10 17 42](https://github.com/user-attachments/assets/ee1d032f-55cd-4c7d-820b-6c4affbaa1bf)

**1. Primeira coisa que eu fiz foi analisar o hash da Sofia (hostname) no site [Virus Total](https://www.virustotal.com/gui/file/7bcd31bd41686c32663c7cabf42b18c50399e3b3b4533fc2ff002d9f2e058813/details). No qual, vi que o arquivo de fato é suspeito.**
![Captura de Tela 2024-08-02 às 10 21 46](https://github.com/user-attachments/assets/7339ef80-a4b9-40cd-a755-45d5f5e3f89c)

**2. Após procurar esse hash de arquivo no site [Any Run](https://any.run/), fui começar a fazer a análise dinâmica do arquivo.**
![Captura de Tela 2024-08-02 às 11 20 56](https://github.com/user-attachments/assets/0ce70e22-fefa-4b78-9419-4ca8bec6b1f8)

**3. Se aprofudando mais no caso, alguns dos aspcetos do malwares se propaga no file cscript.exe! e depois vi que alguns arquivos foi modificado.**
![Captura de Tela 2024-08-02 às 11 31 34](https://github.com/user-attachments/assets/07ff8c94-fbd9-480a-862c-a18801219fef)

**4. Verifiquei novamente os hashes de alguns desses arquivos no VirusTotal e descobri que eles foram sinalizados como maliciosos.
Outro aspecto legal é o arquivo xx.vbs que foi executado. Este arquivo pode conter uma instrução de linha de comando para executar um arquivo vbsscript que contém código malicioso, como baixar e executar malware adicional ou roubar dados confidenciais.**

**5. Depois de ficar algum tempo observando, vi que o caso se trata de uma tentativa maliciosa.**
![Captura de Tela 2024-08-02 às 12 09 50](https://github.com/user-attachments/assets/ab16a2d6-03a0-41b8-84ea-71d8587c0194)

![Captura de Tela 2024-08-02 às 12 28 51](https://github.com/user-attachments/assets/05626a78-bcb7-47bc-b3eb-f1f0bd13529b)

![Captura de Tela 2024-08-02 às 12 30 47](https://github.com/user-attachments/assets/9f62573a-ebe7-4c20-b420-a0f4644e6f61)

![Captura de Tela 2024-08-02 às 12 32 22](https://github.com/user-attachments/assets/447c2430-bcd5-46c7-8707-a69220fba298)


![Captura de Tela 2024-08-02 às 12 03 10](https://github.com/user-attachments/assets/4cac9418-55e7-4ad4-ac48-7df4f9ec2804)

![Captura de Tela 2024-08-02 às 12 34 13](https://github.com/user-attachments/assets/cd0bf34d-1d5b-439a-bb4d-d474d2dd9b4e)
