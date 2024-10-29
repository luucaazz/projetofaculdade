Aqui está um código básico de aplicativo de mensagens em React Native que permite a comunicação entre 50 usuários, o envio de fotos e uma área para receber feedback. Este exemplo utiliza o Firebase como backend para simplificar o armazenamento e troca de mensagens e imagens. Certifique-se de configurar um projeto no Firebase e habilitar Authentication e Firestore Database.

Passos iniciais:
Configure o Firebase conforme a documentação do Firebase para Android e iOS.

1. Configurar o Firebase
Projeto no Firebase: Crie um novo projeto no Firebase Console.
Adicionar o Firebase ao App: No projeto Firebase, adicione um aplicativo Android. Isso irá gerar um arquivo google-services.json que deve ser colocado na pasta android/app do projeto.
Habilitar Authentication: No Firebase, vá para a seção Authentication e ative o modo de autenticação Anônimo.
Habilitar Firestore Database: Em Firestore Database, configure um novo banco de dados e defina as regras de segurança para permitir leituras e gravações de dados enquanto está em desenvolvimento.

