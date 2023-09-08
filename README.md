<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clínica Médica</title>
    <style>
        body {
            
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
           
            background-color: rgb(188, 188, 245);
        }
            font-family: Arial, sans-serif;
        }
        h1 {
            color: red; 
        }
        p {
            color: rgb(255, 81, 0);
        }
        ul li {
            color: green; 
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAABC1BMVEX////gEH8QkdHfAHkAjM8Ai8/6/v/fAHzu+Pz/+v4AjtD62Ori8fnhCoMimNT97vbiIof50+bkNo/Y7ff74u/M5/Q2ntb4zOP2wNvjLIzpX6RWZbVNa7k+db80esIvfsUmg8jYFYLJHojAJIu2Ko+sL5OjNpeZPJuPQp6GSKJ9Tqbxnsd3UahuV6xkXbBIb7vOG4Wk0evmRJfqaamCwORXrNztgrZstuDzq87vlMHmT5vzr9Drda+Uyeiw1+7g3O3ujbznWKBGptnottbowNy0F4voy+Ou1+7o1enMJ47e4fChKpWULJbYudmMOJt+OJ3ErtR2QqJlS6ixptFaUquYnc5MXLJ+k8thjcrvsvVVAAAKXklEQVR4nO2daXvaxhaAVS0IyYAwm8FJGue2TtO6Wdi9QW03ie+Wtrdp0vz/X3IlwJQ5ZwbNjLZRn3m/JjLzMqukcw6GkTVB/2J82RogWqPxTb/jZf75GXM4G7mW5bpfUXCjf2nN+iWW9M4vXYsqt6NpuaOzoOiWSnI1iNN7kKyflbEfD0Z8fiuswVHR7RXmgj732P04K1c3emNLxG/VjaMyzcZgJCwYdmPzoOh2cxO0JARDxUFZFD2ZHlz3YkkGqvgc3Cq2SrHcXEgLhsvNddGt5+BIaJdAildFtz+eUSJDd6D8VDyjjdHwiE2D9l1Ys6INYvCauNlW/XJ23kdc3dw2KZJWp2iH/eAudOsXzDYHZ030/xVfbLwW7BTreG+fBNdIsa70TDyC7bUu4i45R9/JeR4tlWUGDK2b+GuuwDXuZebNlMdrgsYe81wFv5a6wmvNAWgr5zlzQA5Uq59xMxNwThpaZ3yX9cFlN5k2MhFgvPHeKnjkOci9zbaVSbglWzrmve4GfDPq3mGQuyHvIEXD1FV3RySXUov7+dmBWxJDr04aHvJeGICvRtntAhpyP3bRhsqgDZloQ2XQhky0oTJoQybaUBm0IRNtqAzakIk2VAZtyEQbKoM2ZKINlUEbMtGGyqANmWhDZdCGTLShMmhDJtpQGbQhk7+/oUdGtvEHceSNtCEIf1c3YF/e8JIMF1M2EFre8JoMiqqrGtgmb3gmF7aZO/KGID5c2bwSeUNwpbIpCfKGcCKqOk4TGPZRGoOSigkMcTaRda3gyUY6vtSgZS1azYts15tqrd3usmjXKpRLkhiCo+n6D7iXZ/1DLg4CoS200l7Me6ZtO2zs3oLiCI6XQonL1NRTRlofLdOvPhqfc47r9qTn275v7se3ezV0KXn4ErtFwElhgrhRiQ12ntyW7tSPtds4Nqrw4nECQ7ycylha9ZgFqj11+PRWinN4OZlRIhpyD/Of5LCsGftzKwvO7tvgdMEfIOeS6I2sd5uKYrgIs+6+qne2iJ9p2gvwF8hEO+GU3iDpVNzgMg593YZQB5qUYQoP0KLnkoCSRSwFtYxI1xQVNP0pbCE4QD8TvVnvyFXUwLgtNEUkBClLDcjqffbsZ0HF4DgtxQFQbEsIms4QNvAQGr4Rzpa8EShNtFeRrLFRFZ6DK/CeT+6Iz968+YdoLxqHrXQcLSKNcSq4iq67EC6lIR1iJkaG4oreOa0SgYTiTh75UkpwTjt9E1viyvCbt6KKRnDeoteUEMPdHoyrwnZ+eHKd0Ft3uaO4Nnwnrmh4R7NBdJ7mhW64zXufULrQt81Gj83dBM/Bzfe/c4OxNpRSDOlczY4vRy0umtTSdw+Plmt4lfH96bBdrbDZ07AjZPjtu/dSiis8LoLDC0p9uIf1dIIMnWlbvkk7OesPht+eJlDkxesP8HOC1WZVbcAONO+TfdZ2tXkwPD3NQ5Fyd7JOfEcLaQPeMgjzcLT5qw9Pn+eiiMqIrCpQzMEgtRMLbst9/dWHz58//2fyPxsPfBYSPZSsgEFK28eF2dzqEYbf5aJ4DBLfj8MTKTlI/bt96yQ/q22RNPwlD8UOGKd1zxgCw2U6n+RFiqThdy/yUAQVKKwO3Cvw4yVJouqQpOGLF3kogvoM4aY/JQzxLZ80QctFht9nrwieSobH7x65kCbcCncJWtjw+5/S+/sMxvCNObmUprFVbOmEitDwh8wVyYnojqFhkuMaooP78Icfs1Yk35iH20WWhqEiNnyZsWK+hkbnX8gwa8WcDY2Db1Afvnz575Q/hCBvQ+OQYvgqS8XcDY2Dd+G9BWH46lWWivkbGu/fYcNH2SkWYGi8P0WGn7NTLMJwrUj24aPHWSkWYhgqIsNHrzNSLMbQePsfZPj4STaKBRkab/+LDF8/YT1zTURRhsaHSJE0fP11Fr1YmKHx4Rdk+ORpBorFGUaK0PDJ0/QHaoGGoSIy/PokdcUiDY0PvyLDpydpf2KhhsZvvyLDp07KvRhnmOZTDAq//Q8ZntjpKs7gUwzySZSfxhPvfUSKwPDETHXggFK/M/g0EYbIpM7H35HhSSNFxWCwKxi9uIAvgDM5Z+yyUiQMHaeR3qeCuCyrbywdciKiGJnU+fg7NLT99BThq5kAv+POvBONj39AQzM1RVhWeuAZlR6paKf3XJ/Jpz+goelTQo4lCEAF+1WSGHyNn8oLxBg+fYaGKSnCsLhVNEYXDlMUNpoBnz4/BoahYuLXXh6K+1sXvr+Dis40rVdsbEJFYGjaSRUPUTDGJpR2iAKG7MYic8c/kWHYi0nePx9c49CoTcoHCjeJPqwxXSyZCSXxySV8isAw5hV754jN1c3IxZGp218QuXewYhS6ZtuOHUf4P8zw2+iK93nlT2Ro2lOWYmfWjEkpQX67OS1oJgri205j0hXty8oXZGg6jHjAI0oPxbITSt9OaLi2vBMNcqh+QYaMm5sjsd/83IzR3V8QWdDGqbhjT/Deq/oFGfo9yv+D+zinIfHrE3OZGFrs6MzF5mOkSBpSDxzUH3OLA+RoVpJOxQdHwW6snUBDWrzLrUQXoqySai+VXhQObGyfQEN8dwN/RopLcIwSEoVzglgIHvq60BDv+zDTm6sHKRmXlXkay40pfHRfAkPTR3f8oguNy/q5N8HUNSa22LYxPCENcaLKWMzQqjPzWLp3KXWj2HIDBg++QxVKvnSt8b60wGHDTmP3F7tLADfh/h36H/zZUK41iklEqgzveNNk9yD4oAAEYjfQ+Y8zp8213FuORKtKd9KznYSaKL10L/DUiEdAcGvtP7i5rsWX6LyhtpxMew0ewv6ipQ5TRtoewP2bTxvjR+NmnU2zdXzRz6hAQaW2nFNS+4RijWtgAGT/uE+U2gQ5CnUi6MOUX2SkA04ixvs2mzIYhudaoMjKbaNeXAZDnIaK1/w915bBED13dfiHaUkMYXoRPl4yKYshWPMFEhvKYghfttKeuNApjeE9uIfmXmpKY9h2JBtaGkOQE86/mJbGsEIa8sfmlMdQNvpIGyqDNmSiDZVBGzLRhsqgDZloQ2XQhky0oTJoQybaUBm0IRNtqAzakIk2VAZtyEQbKoM2ZKINlUEbMtGGyqANmWhDZfj7G0rX2GgT15m+uoZkBCZ/8QIY9Jd9GrIsshV7F6CWcTrlqLMA1NjgrboMEufEouDz5V6uxkYX5D0JRBfnDQhs4+1EEEDtpFRSPAtgBXu+mYhSdNVdSnGyLU+c8BKGwCs8DdGMCpsbq7gEV+RRIScBsBRM9ItCe+diZYLzAdXdDSNwjQ2/MWQ2ubrE2cd51MdJAq3Ghs2osTGc05IdFT6UrqHWLvDpNTVo+X+qd6GBNjdRUqz6lRWoZJEQaf42Q2ZQVkd+QfXHaMRUuheTFRnKD5Soxy1Ygkm4pian6Cf/Ka3ckFIsk2A4UMV/FDOlonv5MRGszWBTfxFTabo9gV3DaSh818uGt8aGb5uL0nXgmuqwRz98kn69Rclm4C6V7rxnOyzLqOhdY74saf9tqdTuGTU2etPJsJ293v8BYvNyf9tLaeIAAAAASUVORK5CYII=" alt="Imagem do cabeçalho">
        <nav>
            <ul>
                <li><a href="index.html">Página Principal</a></li>
                <li><a href="sobre.html">Sobre a Clínica</a></li>
                <li><a href="horario.html">Horário de Atendimento</a></li>
                <li><a href="contato.html">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Content -->
    <div id="content">
        <!-- Página Principal -->
        <section id="pagina-principal">
            <h1>Bem-vindo à Clínica Médica</h1>
            <p>Oferecemos serviços médicos de alta qualidade para cuidar da sua saúde.</p>
        </section>

        <!-- Sobre a Clínica -->
        <section id="sobre-a-clinica">
            <h1>Sobre a Clínica</h1>
            <p>Aqui na Clínica Médica, estamos comprometidos em proporcionar o melhor atendimento médico para nossos pacientes. Nossa equipe de profissionais altamente qualificados está à sua disposição para cuidar da sua saúde.</p>
        </section>

        <!-- Horário de Atendimento -->
        <section id="horario-de-atendimento">
            <h1>Horário de Atendimento</h1>
            <p>Oferecemos atendimento de segunda a sexta-feira e aos sábados. Confira nossos horários e preços:</p>
            <table>
                <thead>
                    <tr>
                        <th>Serviços</th>
                        <th>Segunda a Sexta</th>
                        <th>Sábados</th>
                        <th>Feriados</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Clínica geral</td>
                        <td>08h - 19h</td>
                        <td>08h - 14h</td>
                        <td>08h - 14h</td>
                    </tr>
                    <tr>
                        <td>Psicologia</td>
                        <td>08h - 19h</td>
                        <td>08h - 14h</td>
                        <td>08h - 14h</td>
                    </tr>
                    <tr>
                        <td>Pediatria</td>
                        <td>08h - 19h</td>
                        <td>08h - 18h</td>
                        <td>-</td>
                    </tr>
                    <tr>
                        <td>Oftalmologia</td>
                        <td>08h - 19h</td>
                        <td>08h - 18h</td>
                        <td>-</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Contato -->
        <section id="contato">
            <h1>Contato</h1>
            <p>Entre em contato conosco para agendar uma consulta ou tirar suas dúvidas.</p>
            <ul>
                <li>Telefone: (11) 1234-5678</li>
                <li>WhatsApp: (11) 98765-4321</li>
                <li>Endereço: Rua da Clínica, 1234 - Cidade</li>
            </ul>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d12345.67890!2d-46.7890123!3d-23.4567890!4m12!1m6!3m5!1s0x0000000000000000:0x0123456789abcdef!2sNome+da+Cl%C3%ADnica!8m2!3d-23.4567890!4d-46.7890123!3m4!1s0x0000000000000000:0x0123456789abcdef!8m2!3d-23.4567890!4d-46.7890123" width="400" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
            <form action="enviar.php" method="post">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>

                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required>

                <label for="assunto">Assunto:</label>
                <input type="text" id="assunto" name="assunto" required>

                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" rows="4" required></textarea>

                <button type="submit">Enviar</button>
                <button type="reset">Limpar</button>
            </form>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>Entre em contato: (11) 1234-5678 | Endereço: Rua da Clínica, 1234 - Cidade</p>
    </footer>
</body>
</html>
