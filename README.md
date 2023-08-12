# commandsCopy

|-----------------------------|

Gerar migration com TypeOrm

npm run migration:generate -- src/database/migrations/NameOfMigration

. 1 Utilizar local onde quer salvar a migration <br>
. 2 Se não estiver gerando ou encontrando modificacoes no schema, pode ser o local "src" errado no typeorm.config <br>
. 3 Se estiver dando erro de import no render, é porque a entitie e migration precisa apontar para a build(.js) e não src(.ts)

Rodar sql e criar tabelas banco

npm run migration:run

---

As generates de migrations não são muito confiaveis, elas não adicionam Cascade mesmo tenho a informação setada na entidade.

|------------------------------|
