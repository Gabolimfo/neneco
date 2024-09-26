// Função para adicionar fotos
function adicionarFoto() {
    const input = document.getElementById('uploadFoto');
    const galeria = document.getElementById('galeria');

    if (input.files && input.files[0]) {
        const reader = new FileReader();
        reader.onload = function (e) {
            const img = document.createElement('img');
            img.src = e.target.result;
            galeria.appendChild(img);
        }
        reader.readAsDataURL(input.files[0]);
    }
}

// Função para adicionar textos
function adicionarTexto() {
    const textoInput = document.getElementById('textoInput').value;
    const textosPublicados = document.getElementById('textosPublicados');

    if (textoInput.trim()) {
        const texto = document.createElement('p');
        texto.textContent = textoInput;
        textosPublicados.appendChild(texto);
        document.getElementById('textoInput').value = ''; // Limpa o campo
    } else {
        alert('Escreva algo antes de publicar!');
    }
}

// Função para adicionar cartas
function adicionarCarta() {
    const cartaInput = document.getElementById('cartaInput').value;
    const cartasEnviadas = document.getElementById('cartasEnviadas');

    if (cartaInput.trim()) {
        const carta = document.createElement('p');
        carta.textContent = cartaInput;
        cartasEnviadas.appendChild(carta);
        document.getElementById('cartaInput').value = ''; // Limpa o campo
    } else {
        alert('Escreva algo antes de enviar!');
    }
}
