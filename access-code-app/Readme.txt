run this script from powershell ise

$postParams = @{accessCode='54321'}
Invoke-WebRequest -Uri http://localhost:82/validate-accesscode -Method POST -Body $postParams

$postParams = @{accessCode='88888'}
Invoke-WebRequest -Uri http://localhost:82/validate-accesscode -Method POST -Body $postParams
