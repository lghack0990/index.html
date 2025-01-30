const respuesta = await fetch('https://robot-cerebro.onrender.com/chat', {
         method: 'POST',
         headers: {
             'Content-Type': 'application/json',
         },
         body: JSON.stringify({ mensaje }),
     });
