# debug_php
utilisable sur vos projet PHP
comme ceci:
=>> $data = vos données ou un tableau array ou object en forme de tableau (object) array();
=>> $exitAfter = Une seule instance possible met fin au script par un die();
=>> $collapse = Sert si vous voulez les données directement affichées ou "remballé"

# Utilisations :
echo new Debug($data, $exitAfter, $collapse);
ou
simplement:
debug($data);

# Credit :
php.net modifié par moi: stive@determe.be pour le CMS https://bel-cms.dev
