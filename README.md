$.ajax({
  type: 'GET',
  url: 'https://wakatime.com/share/@SecurityR4t/9fcf9eb9-ac15-40e4-aacb-1a52d38bbd1b.json',
  dataType: 'jsonp',
  success: function(response) {
    console.log(response.data);
  },
});
