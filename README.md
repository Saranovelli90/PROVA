# PROVA
@@ -0,0 +1,17 @@
var options = {
    "method": "POST",
    "hostname": "staging.api.scalapay.com",
    "port": null,
    "path": null,
    "headers": {
      "Accept": "application/json",
      "Content-Type": "application/json",
      "Authorization": "Bearer qhtfs87hjnc12kkos"
    }
};

// TODO hostname should be a param, I want to be able to switch from dev to staging to prod

module.exports = {
    options
} 
