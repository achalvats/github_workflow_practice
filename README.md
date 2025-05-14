command to run repsoitry dispatch (use gitbash terminal)
curl.exe -X POST  \
-H "Accept: application/vnd.github+json" \
-H "Authorization: Bearer github_token" \
-d '{"event_type": "webhook", "client_payload": {"message": "Hello from curl!"} }' \
https://api.github.com/repos/achalvats/github_workflow_practice/dispatches
