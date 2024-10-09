$(document).ready(function () {

  $("#contenidoInterno").load("borrar.html");

  $("#hide1").hide();
  $("#hide2").hide();
  $("#hide3").hide();
  $("#hide4").hide();
  $("#hide5").hide();
  $("#hide6").hide();

  $("#Tiramisú").click(function () {
    $("#hide1").show(3000);
  });
  $("#btnHide1").click(function () {
    $("#hide1").hide(2000);
  });

  $("#Cheesecakes").click(function () {
    $("#hide2").show(3000);
  });
  $("#btnHide2").click(function () {
    $("#hide2").hide(2000);
  });

  $("#Roles de Canela").click(function () {
    $("#hide3").show(3000);
  });
  $("#btnHide3").click(function () {
    $("#hide3").hide(2000);
  });

  $("#Donas").click(function () {
    $("#hide4").show(3000);
  });
  $("#btnHide4").click(function () {
    $("#hide4").hide(2000);
  });

  $("#btnShow5").click(function () {
    $("#hide5").show(3000);
  });
  $("#btnHide5").click(function () {
    $("#hide5").hide(2000);
  });

  $("#btnShow6").click(function () {
    $("#hide6").show(3000);
  });
  $("#btnHide6").click(function () {
    $("#hide6").hide(2000);
  });

  $("#ArrozconLeche").click(function () {
    $("#hide7").show(3000);
  });
  $("#btnHide7").click(function () {
    $("#hide7").hide(2000);
  });

  $("#Cafe").click(function () {
    $("#hide8").show(3000);
  });
  $("#btnHide8").click(function () {
    $("#hide8").hide(2000);
  });


  $("#send").click(function () {
    var nombre_gato = document.getElementById('inf1').value;
    var nombre_usuario = document.getElementById('inf2').value;
    var edad_usuario = document.getElementById('inf3').value;
    var email = document.getElementById('inf4').value;
    var telefono = document.getElementById('inf5').value;

    $.ajax({
      type: "post",
      url: "http://127.0.0.1:5000/adopcion",
      data:
      {
        'nombre_gato': nombre_gato,
        'nombre_usuario': nombre_usuario,
        'edad_usuario': edad_usuario,
        'email': email,
        'telefono': telefono,
      },
      success: function () {
        alert('Información Enviada');

        $('#inf1').val('');
        $('#inf2').val('');
        $('#inf3').val('');
        $('#inf4').val('');
        $('#inf5').val('');
      }
    });
    return false;
  });


  var ultimaInformacion = null;
  function actualizarTabla() {
    $.get("http://127.0.0.1:5000/adopcion", function (response) {
      var data = response.adopciones;

      if (JSON.stringify(data) !== JSON.stringify(ultimaInformacion)) {
        $("#tabla_resultados tbody").empty();

        data.forEach(function (adopcion) {
          var nuevaFila = "<tr><td>" + adopcion[0] + "</td><td>" + adopcion[1] + "</td><td>" + adopcion[2] + "</td><td>" + adopcion[3] + "</td><td>" + adopcion[4] + "</td><td>" + adopcion[5] + "</td></tr>";
          $("#tabla_resultados tbody").append(nuevaFila);
        });

        ultimaInformacion = data;
      }
    });
  }

  setInterval(actualizarTabla, 5000);


  function obtenerItems() {
    $.get("http://127.0.0.1:5000/datos", function (data) {
      $("#tabla_comida").empty();
      for (var i = 0; i < data.items.length; i++) {
        var item = data.items[i];
        var boton = '<button class="btn btn-info btnComida" id="' + item + '">' + item + '</button>';
        $("#tabla_comida").append(boton);
      }
    });
  }


  obtenerItems();

  $("#tabla_comida").on("click", ".btnComida", function () {
    var id = $(this).attr('id');
    $("#hide1, #hide2, #hide3, #hide4, #hide7, #hide8").hide();
    $("#" + id).show(3000);
  });



  $.ajax({
    url: 'http://127.0.0.1:5000/precios',
    method: 'GET',
    success: function (data) {
      data.forEach(function (producto) {
        $('#precio' + producto[0]).text('$' + producto[1]);
      });
    }
  });

  $.ajax({
    url: 'http://127.0.0.1:5000/gatos',
    method: 'GET',
    success: function (data) {
      data.forEach(function (gato) {
        $('#nombre_gato' + gato[0]).text(gato[1]);
        $('#edad_gato' + gato[0]).text(gato[2]);
        $('#pelo_gato' + gato[0]).text(gato[3]);
        $('#comportamiento_gato' + gato[0]).text(gato[4]);
      });
    }
  });


});


