# kubernetes-agent-config
## Description
* Репозиторий содержит настойки доступа к gitlab KAS.
* Агент доступен только проектам в тоё-же группе или подчинённых подгруппах.
* [.gitlab-ci.yml](https://github.com/FZEN475/kubernetes-agent-config/blob/main/.gitlab-ci.yml) - для проверки доступов.
* <details><summary> Agents list. </summary>

  | Name                  | Namespace | Gitlab groups/project access | Comment                                      |
  |:----------------------|:----------|:-----------------------------|:---------------------------------------------|
  | kubernetes-agent-dev  | dev       | dev/*                        | Имеет полные права в пространстве имён dev.  |
  | kubernetes-agent-prod | prod      | dev/*                        | Имеет полные права в пространстве имён prod. |

  </details>
