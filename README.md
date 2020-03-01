# Angular_Apollo
Angular と Apollo Clientを試してみる

- Nx で空のプロジェクトを作る
npx create-nx-workspace
workspace name?
angular CLI select

- Angular をフロントエンドプロジェクトとして追加する
ng add @nrwl/angular
Cypress select
ng g @nrwl/angular:app frontend
SASS select
routing ? yes
ng serve 
- Nestjs  をバックエンドプロジェクトとして追加する
ng add @nrwl/nest
ng g @nrwl/nest:app backend --frontend-project frontend
which directory  no input
ng serve backend
- Apollo Clientを Angular プロジェクトに追加する
ng add apollo-angular