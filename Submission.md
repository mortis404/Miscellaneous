
# BCGDV Internship Application Instructions

---

## Generating an API key

`curl -i -H "Accept: application/json" -H "Content-Type: application/json" -X GET https://interns.bcgdvsydney.com/api/v1/key`

Response: `{"key": "7293588d-f7ec-4602-b609-7ab3f86a1e33", "expires": "2019-08-20 22:35:29.511237"}`

## Application Submission

Making the post request: 

`curl -d '{"name": "Anirudh V. Kasturi", "email": "ak.anirudhkasturi@gmail.com"}' -H "Content-Type: application/json" -X POST https://interns.bcgdvsydney.com/api/v1/submit?apiKey=7293588d-f7ec-4602-b609-7ab3f86a1e33`