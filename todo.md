

- Function: type de retour
- Variable: type
- block data: Contient des variables
- externalProcedure —|> TbehavihorialENtity
- externalProcedure —|> TWithStatements
- externalProcedure —|> TInvocable
- FortranParameter —|> TParameter
- Variable —|> TStructuralEntity
- Programunit —|> tWithAccess
- Enlever sousProg
- Utiliser une pile pour le parser. À la creation on met dans la pile, à la fin on dépile.



—— réponse GitHub
- Repo non dispo
- Bonne idée pour savoir le type de la classe à créer.
- About the naming, garder les prefix pour faire le lien avec l’AST
- Pas util pour nous. pas de scenario ou ça peut être utile


——— recap
- refaire l’UML
- À partir du UML faire le metamodel
- Completer le parser en creant les classes correspondants aux noeuds et garder une trace du parent sur une pile
- /!\ En deux passage:
    - 1 parser pour créer les objets
    - 2e passer pour faire le lien
   - autre façon; faire un model IR.

————————————————————

#FamixTFunction avec TInvocable issue
