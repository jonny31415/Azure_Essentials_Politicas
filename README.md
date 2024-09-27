# Gerenciando Politicas em Acessos Azure

## Políticas
Podem ser criadas políticas que bloqueiam a criação, modificação e exclusão de determinados recursos. Vale ressaltar que, uma vez configurada, nem mesmo o administrador pode quebrar as regras da política enquanto está ativa. AS políticas de um grupo de recursos são herdadas pelos recursos do grupo. Entretanto, quando movidos, esses recursos perdem os bloqueios herdados. Os métodos de bloqueio são ReadOnly (Apenas Leitura) e Delete (Exclusão)

### ReadOnly
Permite apenas a visualização dos recursos, bloqueando qualquer atualização de estado, mudança de grupo de recurso e exclusão.

### Delete
Permite operações de mudança de estado e mudança de grupo de recursos. Proíbe apenas a exclusão do recurso.

## Microsoft Purview
Essa ferramento oferece visualizações e dados que auxiliam nas áreas de compliance e auditoria.
