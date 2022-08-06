# router.do
Dynamic Router Object Interface

<https://router.do/router.all("*",oauth).get("/",req=\>fetch("https://api.cf")).get("/:resource",withParams,({resource},env)=\>json(env.KV.get(req.id))>
