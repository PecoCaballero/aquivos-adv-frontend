# Frontend Arquivos ADV

Padronização do GIT:

* *Nenhum commit deve ser feito diretamente na branch develop*

* Todo card no Trello deve tornar-se uma nova branch e então as modificações necessárias serão feitas nesta nova branch
  
*  Assim que finalizada a tarefa descrita no trello o dono da branch deve realizar um *merge request* no GitHub. Qualquer outra pessoa pode fazer o code review, aprovar e mergear a branch à develop (o mesmo vale para reprovação de código e solitação de rework).
  
* Antes de começar qualquer branch nova deve ser realizado um pull da develop, para garantir que sua branch local não esteja atrás em commits da origin/develop
  *  ```git pull```



```git add .```

```git commit -m '[NOME_DA_FEATURE] DIGITE_UMA_BREVE_DESCRIÇÃO_AQUI' ```

```git push -u origin NOME_DA_BRANCH ```