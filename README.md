# My site
Hi, I got the question and also understand what I have to do. But as coding requires a practice and also I am not very sharp in django. Also I have to submit some reports and my minors are going to be held from 14. Due to these I was not able to code the full program.

But I got the algorithem to extract the top repos of Google, Microsoft, and Facebook and I extracted All the repos of google from github
Algo:
1. Firstly I Extract all the Repos of google from the github using .get() in my python program by calling the api
2. Now we need the top 10 (Say) repos. For this We use the counts for froks. Higher the Forks count top the reposotory is. So using coding I will extract out top 10 counts of forks
3. And also tha name of each repos
4. Using sort() and direction() we will extract of the oldest m repos


These are all the reposotories of the google 
**Repos** 

{'id': 1936771, 'node_id': 'MDEwOlJlcG9zaXRvcnkxOTM2Nzcx', 'name': 'truth', 'full_name': 'google/truth', 'private': False, 'owner': {'login': 'google', 'id': 1342004, 'node_id': 'MDEyOk9yZ2FuaXphdGlvbjEzNDIwMDQ=', 'avatar_url': 'https://avatars.githubusercontent.com/u/1342004?v=4', 'gravatar_id': '', 'url': 'https://api.github.com/users/google', 'html_url': 'https://github.com/google', 'followers_url': 'https://api.github.com/users/google/followers', 'following_url': 'https://api.github.com/users/google/following{/other_user}', 'gists_url': 'https://api.github.com/users/google/gists{/gist_id}', 'starred_url': 'https://api.github.com/users/google/starred{/owner}{/repo}', 'subscriptions_url': 'https://api.github.com/users/google/subscriptions', 'organizations_url': 'https://api.github.com/users/google/orgs', 'repos_url': 'https://api.github.com/users/google/repos', 'events_url': 'https://api.github.com/users/google/events{/privacy}', 'received_events_url': 'https://api.github.com/users/google/received_events', 'type': 'Organization', 'site_admin': False}, 'html_url': 'https://github.com/google/truth', 'description': 'Fluent assertions for Java 
and Android', 'fork': False, 'url': 'https://api.github.com/repos/google/truth', 'forks_url': 'https://api.github.com/repos/google/truth/forks', 
'keys_url': 'https://api.github.com/repos/google/truth/keys{/key_id}', 'collaborators_url': 'https://api.github.com/repos/google/truth/collaborators{/collaborator}', 'teams_url': 'https://api.github.com/repos/google/truth/teams', 'hooks_url': 'https://api.github.com/repos/google/truth/hooks', 'issue_events_url': 'https://api.github.com/repos/google/truth/issues/events{/number}', 'events_url': 'https://api.github.com/repos/google/truth/events', 'assignees_url': 'https://api.github.com/repos/google/truth/assignees{/user}', 'branches_url': 'https://api.github.com/repos/google/truth/branches{/branch}', 'tags_url': 'https://api.github.com/repos/google/truth/tags', 'blobs_url': 'https://api.github.com/repos/google/truth/git/blobs{/sha}', 'git_tags_url': 'https://api.github.com/repos/google/truth/git/tags{/sha}', 'git_refs_url': 'https://api.github.com/repos/google/truth/git/refs{/sha}', 'trees_url': 'https://api.github.com/repos/google/truth/git/trees{/sha}', 'statuses_url': 'https://api.github.com/repos/google/truth/statuses/{sha}', 'languages_url': 'https://api.github.com/repos/google/truth/languages', 'stargazers_url': 'https://api.github.com/repos/google/truth/stargazers', 'contributors_url': 'https://api.github.com/repos/google/truth/contributors', 'subscribers_url': 'https://api.github.com/repos/google/truth/subscribers', 'subscription_url': 'https://api.github.com/repos/google/truth/subscription', 'commits_url': 'https://api.github.com/repos/google/truth/commits{/sha}', 'git_commits_url': 'https://api.github.com/repos/google/truth/git/commits{/sha}', 'comments_url': 'https://api.github.com/repos/google/truth/comments{/number}', 'issue_comment_url': 'https://api.github.com/repos/google/truth/issues/comments{/number}', 'contents_url': 'https://api.github.com/repos/google/truth/contents/{+path}', 'compare_url': 'https://api.github.com/repos/google/truth/compare/{base}...{head}', 'merges_url': 'https://api.github.com/repos/google/truth/merges', 'archive_url': 'https://api.github.com/repos/google/truth/{archive_format}{/ref}', 'downloads_url': 'https://api.github.com/repos/google/truth/downloads', 'issues_url': 'https://api.github.com/repos/google/truth/issues{/number}', 'pulls_url': 'https://api.github.com/repos/google/truth/pulls{/number}', 'milestones_url': 'https://api.github.com/repos/google/truth/milestones{/number}', 'notifications_url': 'https://api.github.com/repos/google/truth/notifications{?since,all,participating}', 'labels_url': 'https://api.github.com/repos/google/truth/labels{/name}', 'releases_url': 'https://api.github.com/repos/google/truth/releases{/id}', 'deployments_url': 'https://api.github.com/repos/google/truth/deployments', 'created_at': '2011-06-22T18:55:12Z', 'updated_at': '2022-02-10T03:46:18Z', 'pushed_at': '2022-02-07T15:02:55Z', 'git_url': 'git://github.com/google/truth.git', 'ssh_url': 'git@github.com:google/truth.git', 'clone_url': 'https://github.com/google/truth.git', 'svn_url': 'https://github.com/google/truth', 'homepage': 'https://truth.dev/', 'size': 33346, 'stargazers_count': 2389, 'watchers_count': 2389, 'language': 'Java', 'has_issues': True, 'has_projects': True, 'has_downloads': True, 'has_wiki': True, 'has_pages': True, 'forks_count': 246, 'mirror_url': None, 'archived': False, 'disabled': False, 'open_issues_count': 76, 'license': {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='}, 'allow_forking': True, 'is_template': False, 'topics': ['assertion-framework', 'java', 'junit', 'test-framework', 'testing-library', 'truth', 'unit-testing'], 'visibility': 'public', 'forks': 246, 'open_issues': 76, 'watchers': 2389, 'default_branch': 'master', 'permissions': {'admin': False, 'maintain': False, 'push': False, 'triage': False, 'pull': True}}
[10/Feb/2022 23:15:35] "GET / HTTP/1.1" 200 616
{'id': 1936771, 'node_id': 'MDEwOlJlcG9zaXRvcnkxOTM2Nzcx', 'name': 'truth', 'full_name': 'google/truth', 'private': False, 'owner': {'login': 'google', 'id': 1342004, 'node_id': 'MDEyOk9yZ2FuaXphdGlvbjEzNDIwMDQ=', 'avatar_url': 'https://avatars.githubusercontent.com/u/1342004?v=4', 'gravatar_id': '', 'url': 'https://api.github.com/users/google', 'html_url': 'https://github.com/google', 'followers_url': 'https://api.github.com/users/google/followers', 'following_url': 'https://api.github.com/users/google/following{/other_user}', 'gists_url': 'https://api.github.com/users/google/gists{/gist_id}', 'starred_url': 'https://api.github.com/users/google/starred{/owner}{/repo}', 'subscriptions_url': 'https://api.github.com/users/google/subscriptions', 'organizations_url': 'https://api.github.com/users/google/orgs', 'repos_url': 'https://api.github.com/users/google/repos', 'events_url': 'https://api.github.com/users/google/events{/privacy}', 'received_events_url': 'https://api.github.com/users/google/received_events', 'type': 'Organization', 'site_admin': False}, 'html_url': 'https://github.com/google/truth', 'description': 'Fluent assertions for Java 
and Android', 'fork': False, 'url': 'https://api.github.com/repos/google/truth', 'forks_url': 'https://api.github.com/repos/google/truth/forks', 
'keys_url': 'https://api.github.com/repos/google/truth/keys{/key_id}', 'collaborators_url': 'https://api.github.com/repos/google/truth/collaborators{/collaborator}', 'teams_url': 'https://api.github.com/repos/google/truth/teams', 'hooks_url': 'https://api.github.com/repos/google/truth/hooks', 'issue_events_url': 'https://api.github.com/repos/google/truth/issues/events{/number}', 'events_url': 'https://api.github.com/repos/google/truth/events', 'assignees_url': 'https://api.github.com/repos/google/truth/assignees{/user}', 'branches_url': 'https://api.github.com/repos/google/truth/branches{/branch}', 'tags_url': 'https://api.github.com/repos/google/truth/tags', 'blobs_url': 'https://api.github.com/repos/google/truth/git/blobs{/sha}', 'git_tags_url': 'https://api.github.com/repos/google/truth/git/tags{/sha}', 'git_refs_url': 'https://api.github.com/repos/google/truth/git/refs{/sha}', 'trees_url': 'https://api.github.com/repos/google/truth/git/trees{/sha}', 'statuses_url': 'https://api.github.com/repos/google/truth/statuses/{sha}', 'languages_url': 'https://api.github.com/repos/google/truth/languages', 'stargazers_url': 'https://api.github.com/repos/google/truth/stargazers', 'contributors_url': 'https://api.github.com/repos/google/truth/contributors', 'subscribers_url': 'https://api.github.com/repos/google/truth/subscribers', 'subscription_url': 'https://api.github.com/repos/google/truth/subscription', 'commits_url': 'https://api.github.com/repos/google/truth/commits{/sha}', 'git_commits_url': 'https://api.github.com/repos/google/truth/git/commits{/sha}', 'comments_url': 'https://api.github.com/repos/google/truth/comments{/number}', 'issue_comment_url': 'https://api.github.com/repos/google/truth/issues/comments{/number}', 'contents_url': 'https://api.github.com/repos/google/truth/contents/{+path}', 'compare_url': 'https://api.github.com/repos/google/truth/compare/{base}...{head}', 'merges_url': 'https://api.github.com/repos/google/truth/merges', 'archive_url': 'https://api.github.com/repos/google/truth/{archive_format}{/ref}', 'downloads_url': 'https://api.github.com/repos/google/truth/downloads', 'issues_url': 'https://api.github.com/repos/google/truth/issues{/number}', 'pulls_url': 'https://api.github.com/repos/google/truth/pulls{/number}', 'milestones_url': 'https://api.github.com/repos/google/truth/milestones{/number}', 'notifications_url': 'https://api.github.com/repos/google/truth/notifications{?since,all,participating}', 'labels_url': 'https://api.github.com/repos/google/truth/labels{/name}', 'releases_url': 'https://api.github.com/repos/google/truth/releases{/id}', 'deployments_url': 'https://api.github.com/repos/google/truth/deployments', 'created_at': '2011-06-22T18:55:12Z', 'updated_at': '2022-02-10T03:46:18Z', 'pushed_at': '2022-02-07T15:02:55Z', 'git_url': 'git://github.com/google/truth.git', 'ssh_url': 'git@github.com:google/truth.git', 'clone_url': 'https://github.com/google/truth.git', 'svn_url': 'https://github.com/google/truth', 'homepage': 'https://truth.dev/', 'size': 33346, 'stargazers_count': 2389, 'watchers_count': 2389, 'language': 'Java', 'has_issues': True, 'has_projects': True, 'has_downloads': True, 'has_wiki': True, 'has_pages': True, 'forks_count': 246, 'mirror_url': None, 'archived': False, 'disabled': False, 'open_issues_count': 76, 'license': {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='}, 'allow_forking': True, 'is_template': False, 'topics': ['assertion-framework', 'java', 'junit', 'test-framework', 'testing-library', 'truth', 'unit-testing'], 'visibility': 'public', 'forks': 246, 'open_issues': 76, 'watchers': 2389, 'default_branch': 'master', 'permissions': {'admin': False, 'maintain': False, 'push': False, 'triage': False, 'pull': True}}
