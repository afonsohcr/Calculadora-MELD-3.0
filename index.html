<script>
    let hemodialise = 'nao';
    let sexo = 'masculino';

    function selectOption(value) {
        hemodialise = value;
        document.querySelectorAll('#hemodialise-sim, #hemodialise-nao').forEach(option => {
            option.classList.remove('selected');
        });
        document.getElementById(`hemodialise-${value}`).classList.add('selected');
    }

    function selectSexo(value) {
        sexo = value;
        document.querySelectorAll('#sexo-masculino, #sexo-feminino').forEach(option => {
            option.classList.remove('selected');
        });
        document.getElementById(`sexo-${value}`).classList.add('selected');
    }

    function calcularMeldNa() {
        const ln = Math.log;

        let bilirrubina = Math.max(1, parseFloat(document.getElementById('bilirubina').value) || 1);
        let rni = Math.max(1, parseFloat(document.getElementById('rni').value) || 1);
        let creatinina = Math.max(1, parseFloat(document.getElementById('creatinina').value) || 1);
        let sodio = parseFloat(document.getElementById('sodio').value) || 137;
        let albumina = parseFloat(document.getElementById('albumina').value) || 3.5;

        // Limites conforme MELD 3.0
        sodio = Math.max(125, Math.min(137, sodio));
        albumina = Math.max(1.5, Math.min(3.5, albumina));

        // Ajuste da creatinina
        if (creatinina > 3 || hemodialise === 'sim') {
            creatinina = 3;
        }

        // Sexo feminino = 1, masculino = 0
        const feminino = sexo === 'feminino' ? 1 : 0;

        const meld3 = 
            1.33 * feminino +
            4.56 * ln(bilirrubina) +
            0.82 * (137 - sodio) -
            0.24 * (137 - sodio) * ln(bilirrubina) +
            9.09 * ln(rni) +
            11.14 * ln(creatinina) +
            1.85 * (3.5 - albumina) -
            1.83 * (3.5 - albumina) * ln(creatinina) +
            6;

        const resultadoFinal = Math.round(meld3);

        document.getElementById('resultado').innerHTML =
            `MELD 3.0: <span>${resultadoFinal}</span>`;
    }

    function limparCampos() {
        document.getElementById('bilirubina').value = '';
        document.getElementById('rni').value = '';
        document.getElementById('creatinina').value = '';
        document.getElementById('sodio').value = '';
        document.getElementById('albumina').value = '';
        selectOption('nao');
        selectSexo('masculino');
        document.getElementById('resultado').innerHTML = '';
    }

    selectOption('nao');
    selectSexo('masculino');
</script>
