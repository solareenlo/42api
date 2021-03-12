# 42api

## Projects ID

```sh
https://api.intra.42.fr/v2/cursus/21/projects?sort=id
```

| ID   | Name             | Slug                   |
|------|------------------|------------------------|
| 1314 | Libft            | 42cursus-libft         |
| 1315 | miniRT           | minirt                 |
| 1316 | ft_printf        | 42cursus-ft_printf     |
| 1318 | netwhat          | netwhat                |
| 1320 | Exam Rank 02     | exam-rank-02           |
| 1321 | Exam Rank 03     | exam-rank-03           |
| 1322 | Exam Rank 04     | exam-rank-04           |
| 1323 | Exam Rank 05     | exam-rank-05           |
| 1324 | Exam Rank 06     | exam-rank-06           |
| 1326 | cub3d            | cub3d                  |
| 1327 | get_next_line    | 42cursus-get_next_line |
| 1328 | ft_server        | ft_server              |
| 1329 | ft_services      | ft_services            |
| 1330 | libasm           | libasm                 |
| 1331 | minishell        | 42cursus-minishell     |
| 1332 | webserv          | webserv                |
| 1334 | Philosophers     | 42cursus-philosophers  |
| 1335 | ft_containers    | ft_containers          |
| 1336 | ft_irc           | ft_irc                 |
| 1337 | ft_transcendence | ft_transcendence       |
| 1338 | CPP Module 00    | cpp-module-00          |
| 1339 | CPP Module 01    | cpp-module-01          |
| 1340 | CPP Module 02    | cpp-module-02          |
| 1341 | CPP Module 03    | cpp-module-03          |
| 1342 | CPP Module 04    | cpp-module-04          |
| 1343 | CPP Module 05    | cpp-module-05          |
| 1344 | CPP Module 06    | cpp-module-06          |
| 1345 | CPP Module 07    | cpp-module-07          |
| 1346 | CPP Module 08    | cpp-module-08          |
| 1379 | ft_hangouts      | 42cursus-ft_hangouts   |


## API の概要

| API                                              | 概要                                 |
|--------------------------------------------------|--------------------------------------|
| cursus_users/graph/on/created_at/by/day          | 1日のユーザー作成数                  |
| cursus_users?filter[campus_id]=26                | 42 の 26campus のユーザーの概要      |
| users/70782/cursus_users                         | ユーザーのレベルの概要               |
| cursus/21/cursus_users?filter[campus_id]=26      | 42cursus の 26campus ユーザーの概要  |
| projects/1314/projects_users?filter[campus]=26   | 26campus の 1314project の状況       |
| users/70782/projects_users                       | 70782ユーザーの project の詳細       |
| projects/1314/users?filter[primary_campus_id]=26 | 26campus の 1314project を受けた一覧 |

## Projects users
```sh
projects/1314/projects_users/graph/on/created_at/by/day
users/70782/projects_users/graph/on/created_at/by/day
projects_users/graph/on/created_at/by/day
projects_users?filter[campus]=26
```
