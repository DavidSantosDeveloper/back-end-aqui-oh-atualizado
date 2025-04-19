insert into
  "Competecia" (
    "id",
    "name",
    "createdAt",
    "updatedAt",
    "deletedAt"
  )
overriding system value
values
  (
    'cm5uc3ing0000kkv8mi759vsq',
    'Competência de Teste',
    '2025-01-13 00:57:06.603',
    '2025-01-13 00:57:06.603',
    null
  );





insert into
  "User" (
    "id",
    "email",
    "name",
    "password",
    "passwordSalt",
    "competeciaId",
    "createdAt",
    "updatedAt",
    "deletedAt"
  )
overriding system value
values
  (
    'cm5uc3iog0002kkv84vfs2m1z',
    'fulano@gmail.com',
    'Fulano',
    '3Qzz9hwIzQPsiywAp5l-KWX9akdNOuDAvKDQfPTFuj7HrE6cYJeaKfqe4LEnRsFZpt44f5UHMkwhCMrvk6CUWw',
    'E5S4Up6BAzg',
    'cm5uc3ing0000kkv8mi759vsq',
    '2025-01-13 00:57:06.64',
    '2025-01-13 00:57:06.64',
    null
  );

insert into
  "User" (
    "id",
    "email",
    "name",
    "password",
    "passwordSalt",
    "competeciaId",
    "createdAt",
    "updatedAt",
    "deletedAt"
  )
overriding system value
values
  (
    'cm5uc3ip00004kkv8c6wxgpce',
    'cicrano@gmail.com',
    'Cicrano',
    '5JJ-Ci-133L3DEwsmJ0qa-pbcTnNgJdbiymFMTkIjeJi4EccAyO9dwC2uhiex7lnMhI4IrlD-BBfquPC0_jBTg',
    'ZK_TuaRta0M',
    null,
    '2025-01-13 00:57:06.66',
    '2025-01-13 00:57:06.66',
    null
  );



insert into
  "Reclamacao" (
    "id",
    "title",
    "status",
    "competeciaId",
    "userId",
    "createdAt",
    "updatedAt",
    "deletedAt"
  )
overriding system value
values
  (
    'cm5uc3ipr0006kkv8pikaud2v',
    'Buraco na rua Antônio Ribeiro',
    'aberto',
    'cm5uc3ing0000kkv8mi759vsq',
    'cm5uc3iog0002kkv84vfs2m1z',
    '2025-01-13 00:57:06.687',
    '2025-01-13 00:57:06.687',
    null
  );

insert into
  "Reclamacao" (
    "id",
    "title",
    "status",
    "competeciaId",
    "userId",
    "createdAt",
    "updatedAt",
    "deletedAt"
  )
overriding system value
values
  (
    'cm5uc3ipz0008kkv8ddob95uq',
    'Problema de iluminação na rua Marcos Silva',
    'aberto',
    'cm5uc3ing0000kkv8mi759vsq',
    'cm5uc3iog0002kkv84vfs2m1z',
    '2025-01-13 00:57:06.696',
    '2025-01-13 00:57:06.696',
    null
  );

insert into
  "Reclamacao" (
    "id",
    "title",
    "status",
    "competeciaId",
    "userId",
    "createdAt",
    "updatedAt",
    "deletedAt"
  )
overriding system value
values
  (
    'dasdasdasdas',
    'vazamento de água na  Rua Oliveira Prado',
    'aberto',
    'cm5uc3ing0000kkv8mi759vsq',
    'cm5uc3iog0002kkv84vfs2m1z',
    '2025-01-13 00:57:06.687',
    '2025-01-13 00:57:06.687',
    null
  );




insert into
  "Mensagem" (
    "id",
    "text",
    "dth",
    "image",
    "lat",
    "lng",
    "reclamacaoId",
    "userId",
    "createdAt",
    "updatedAt",
    "deletedAt"
  )
overriding system value
values
  (
    'cm5uc3iqf0009kkv8sop5ui0z',
    'Gostaria de registrar uma denúncia sobre um problema que está acontecendo na Rua Antônio Ribeiro. Tem um buraco bem grande no meio da rua, que está dificultando a passagem de carros e também é perigoso para pedestres, principalmente à noite, porque é difícil de enxergar. Já vi alguns motoristas precisando desviar de repente, e isso pode acabar causando um acidente. Acho importante que a prefeitura tome providências para sinalizar e consertar o buraco o mais rápido possível, antes que aconteça algo mais grave.',
    '2025-01-13 00:57:06.71',
    'https://th.bing.com/th/id/OIP.dIW9qe3--A4I-gMSjtjQjgHaFi?w=800&h=599&rs=1&pid=ImgDetMain',
    null,
    null,
    'cm5uc3ipr0006kkv8pikaud2v',
    'cm5uc3iog0002kkv84vfs2m1z',
    '2025-01-13 00:57:06.711',
    '2025-01-13 00:57:06.711',
    null
  );

insert into
  "Mensagem" (
    "id",
    "text",
    "dth",
    "image",
    "lat",
    "lng",
    "reclamacaoId",
    "userId",
    "createdAt",
    "updatedAt",
    "deletedAt"
  )
overriding system value
values
  (
    'fdsfsdfsdsdff',
    'Gostaria de registrar uma denúncia sobre um vazamento de água na Rua Oliveira Prado. Tem água limpa escorrendo de uma tubulação quebrada na calçada há vários dias, o que está desperdiçando água e deixando a área escorregadia para pedestres. Além disso, o acúmulo de água está formando poças que podem atrair mosquitos. É importante que o problema seja resolvido rapidamente para evitar maiores danos e desperdício.',
    '2025-01-13 00:57:06.71',
    'https://th.bing.com/th/id/R.8f4eb20cbd3d46961f537341729a8b5d?rik=ZR6IlXezWo7Fpg&pid=ImgRaw&r=0',
    null,
    null,
    'dasdasdasdas',
    'cm5uc3iog0002kkv84vfs2m1z',
    '2025-01-13 00:57:06.711',
    '2025-01-13 00:57:06.711',
    null
  );

insert into
  "Mensagem" (
    "id",
    "text",
    "dth",
    "image",
    "lat",
    "lng",
    "reclamacaoId",
    "userId",
    "createdAt",
    "updatedAt",
    "deletedAt"
  )
overriding system value
values
  (
    'sdfsafdaf',
    'Gostaria de registrar uma denúncia sobre a falta de iluminação na Rua Marcos Silva. Os postes de luz estão apagados há alguns dias, deixando a rua completamente escura durante a noite. Isso tem preocupado muito os moradores, pois aumenta o risco de acidentes e também a sensação de insegurança na região. Seria importante que a prefeitura verificasse e resolvesse o problema o mais rápido possível, para garantir a segurança de todos que passam por lá.',
    '2025-01-13 00:57:06.71',
    'https://1.bp.blogspot.com/-gCa5m4YosL0/VMGEEwnaytI/AAAAAAAADgw/Zg-UHwmxwF4/s1600/Imagem2.jpg',
    null,
    null,
    'cm5uc3ipz0008kkv8ddob95uq',
    'cm5uc3iog0002kkv84vfs2m1z',
    '2025-01-13 00:57:06.711',
    '2025-01-13 00:57:06.711',
    null
  );


