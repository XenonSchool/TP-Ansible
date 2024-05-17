# TP-Ansible

Je déploie l'architecture et la machine via terraform. J'ouvre également le port 3000 via terraform et non pas par ansible.

J'ai testé plusieurs moyens de déployer semaphore :

  - J'ai commencé à l'installer via un playbook avec **snapd**, cela a fonctionné mais je n'ai pas réussi à le configurer BoltDB.
  - J'ai ensuite installé semaphore via un **dockercompose** directement dans le playbook. J'aurai pu externaliser le dockercompose, et le copier directement sur la cible via un **copy** dans le playbook.



