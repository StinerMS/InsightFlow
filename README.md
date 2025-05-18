# InsightFlow
Dashboard empresarial com Laravel, Livewire e IA (Python), dockerizado (não utiliza Sail) e otimizado para CI/CD. Desenvolvido como portfólio para demonstrar integrações complexas e análise preditiva.


git clone https://github.com/StinerMS/InsightFlow.git

cd InsightFlow

docker-compose up -d

docker-compose exec app composer install

cp src/.env.example src/.env
