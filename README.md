# flutter-whereby

Generate room with cURL:
curl https://api.whereby.dev/v1/meetings \
  --header "Authorization: Bearer $YOUR_API_KEY" \
  --header "Content-Type: application/json" \
  --request POST \
  --data @- << EOF
{
  "endDate": "2099-02-18T14:23:00.000Z",
  "fields": ["hostRoomUrl"]
}
EOF
