<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pensamiento Crítico - 12 Temas</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0a0a0a;
            color: #e0e0e0;
            line-height: 1.8;
        }

        /* Menú de navegación */
        nav {
            background: linear-gradient(180deg, #1a1a1a 0%, #0a0a0a 100%);
            padding: 20px;
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            border-bottom: 2px solid #00d4ff;
            box-shadow: 0 4px 20px rgba(0, 212, 255, 0.2);
        }

        nav h1 {
            text-align: center;
            color: #00d4ff;
            margin-bottom: 15px;
            font-size: 1.5rem;
            text-transform: uppercase;
            letter-spacing: 3px;
        }

        .menu {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
        }

        .menu a {
            color: #888;
            text-decoration: none;
            padding: 8px 16px;
            border: 1px solid #333;
            border-radius: 5px;
            transition: all 0.3s ease;
            font-size: 0.9rem;
        }

        .menu a:hover {
            background: #00d4ff;
            color: #0a0a0a;
            border-color: #00d4ff;
            transform: translateY(-2px);
        }

        /* Contenido principal */
        main {
            margin-top: 140px;
            padding: 20px;
            max-width: 1000px;
            margin-left: auto;
            margin-right: auto;
        }

        section {
            background: linear-gradient(145deg, #151515 0%, #0d0d0d 100%);
            margin-bottom: 40px;
            padding: 30px;
            border-radius: 15px;
            border: 1px solid #222;
            scroll-margin-top: 160px;
            transition: all 0.3s ease;
        }

        section:hover {
            border-color: #00d4ff;
            box-shadow: 0 0 30px rgba(0, 212, 255, 0.1);
        }

        section h2 {
            color: #00d4ff;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #333;
            font-size: 1.8rem;
        }

        section h3 {
            color: #ff6b6b;
            margin: 25px 0 10px 0;
            font-size: 1.2rem;
        }

        section p {
            margin-bottom: 15px;
            text-align: justify;
        }

        section ul {
            margin-left: 20px;
            margin-bottom: 15px;
        }

        section li {
            margin-bottom: 8px;
            color: #bbb;
        }

        .concept {
            background: #1a1a1a;
            padding: 15px 20px;
            border-left: 4px solid #00d4ff;
            margin: 15px 0;
            border-radius: 0 10px 10px 0;
        }

        .concept strong {
            color: #00d4ff;
        }

        .quote {
            background: #0f0f0f;
            padding: 15px 20px;
            border-left: 4px solid #ff6b6b;
            margin: 15px 0;
            font-style: italic;
            color: #aaa;
            border-radius: 0 10px 10px 0;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 30px;
            background: #0a0a0a;
            border-top: 1px solid #222;
            color: #666;
            margin-top: 40px;
        }

        /* Botón volver arriba */
        .back-to-top {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background: #00d4ff;
            color: #0a0a0a;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            text-align: center;
            line-height: 50px;
            text-decoration: none;
            font-weight: bold;
            box-shadow: 0 4px 15px rgba(0, 212, 255, 0.4);
            transition: all 0.3s ease;
        }

        .back-to-top:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 20px rgba(0, 212, 255, 0.6);
        }

        /* Responsive */
        @media (max-width: 768px) {
            .menu a {
                padding: 6px 12px;
                font-size: 0.8rem;
            }
            
            section {
                padding: 20px;
            }
            
            section h2 {
                font-size: 1.4rem;
            }
        }
    </style>
</head>
<body>

    <nav>
        <h1>Pensamiento Crítico</h1>
        <div class="menu">
            <a href="#tema1">Tema 1</a>
            <a href="#tema2">Tema 2</a>
            <a href="#tema3">Tema 3</a>
            <a href="#tema4">Tema 4</a>
            <a href="#tema5">Tema 5</a>
            <a href="#tema6">Tema 6</a>
            <a href="#tema7">Tema 7</a>
            <a href="#tema8">Tema 8</a>
            <a href="#tema9">Tema 9</a>
            <a href="#tema10">Tema 10</a>
            <a href="#tema11">Tema 11</a>
            <a href="#tema12">Tema 12</a>
        </div>
    </nav>

    <main>
        <!-- TEMA 1 -->
        <section id="tema1">
            <h2>Tema 1: ¿Por qué pensamos lo que pensamos?</h2>
            
            <h3>El origen del pensamiento</h3>
            <p>Gran parte de lo que se piensa se aprende en algún lugar, comenzando en el núcleo familiar. Se convive diariamente con el entorno, lo que provoca que se aprenda de este sin notarlo.</p>

            <h3>Las tres influencias</h3>
            <p>Las decisiones no se construyen solo por rasgos individuales, sino que se ven profundamente influenciadas por el entorno: <strong>la cultura, la familia y el ambiente</strong>.</p>

            <h3>Cultura y lenguaje</h3>
            <div class="concept">
                <strong>Cultura:</strong> Cimentada en costumbres, tradiciones, normas y el modo en que un grupo piensa de sí mismo. Orienta lo que se percibe como normal, aceptable o deseable.
            </div>
            <div class="concept">
                <strong>Lenguaje:</strong> El idioma no solo es una herramienta de comunicación, sino también un vehículo que organiza el pensamiento y marca límites sobre lo que se considera posible o imposible de expresar.
            </div>

            <h3>Familia y sociedad</h3>
            <p><strong>Familia:</strong> La principal escuela de convivencia. Los progenitores y otros miembros de la familia enseñan qué es importante, cómo comportarse según el contexto y cuáles emociones son aceptables.</p>
            <p><strong>Entorno social:</strong> La escuela, el grupo de amigos y los medios de comunicación ejercen un papel importante en la elaboración del pensamiento.</p>

            <h3>Teoría de vygotsky</h3>
            <div class="quote">"Los patrones de pensamiento de los individuos no provienen de factores innatos, sino que se forman a través de las interacciones entre las personas."</div>

            <h3>Pensamiento crítico</h3>
            <p>Gran parte de lo que se considera pensamiento autónomo tiene, en realidad, raíces colectivas. Desarrollar un pensamiento crítico permite cuestionar de dónde provienen las ideas para diferenciar lo que responde a intereses personales de lo que se repite por influencia externa.</p>
        </section>

        <!-- TEMA 2 -->
        <section id="tema2">
            <h2>Tema 2: Pensar bien vs. pensar rápido</h2>

            <h3>Pensar rápido</h3>
            <div class="quote">"Es automático: el cerebro usa atajos para ahorrar tiempo y energía. Este tipo de pensamiento automático, también conocido como pensamiento intuitivo, es resultado de la experiencia acumulada."</div>

            <h3>Pensar bien</h3>
            <div class="quote">"Requiere más tiempo y dedicación. Es necesario detenerse, cuestionar, analizar diferentes puntos de vista y valorar los resultados de las decisiones."</div>

            <h3>La importancia de la pausa</h3>
            <p>Tomarse el tiempo necesario para pensar favorece la construcción de soluciones más razonadas y con mayor probabilidad de éxito. El pensamiento reflexivo se relaciona estrechamente con la autorregulación.</p>

            <h3>Errores comunes al razonar (sesgos)</h3>
            <p><strong>Sesgos cognitivos:</strong> Fenómenos psicológicos que alteran la información que se percibe a través de los sentidos y que hacen que se distorsione la realidad.</p>
            
            <ul>
                <li><strong>Sesgo de confirmación:</strong> Ocurre cuando solo se busca información que respalde lo que se piensa, ignorando la que contradice esas ideas.</li>
                <li><strong>Razonamiento emocional:</strong> Las emociones interfieren en el desarrollo de la toma de decisiones.</li>
                <li><strong>Pensamiento dicotómico:</strong> Interpretar la realidad en términos absolutos.</li>
                <li><strong>Generalización apresurada:</strong> Sacar conclusiones vagamente definidas a partir de una muestra reducida.</li>
                <li><strong>Apelación a la autoridad:</strong> Dar por hecho que algo es verdadero solo porque lo afirma una figura de autoridad.</li>
            </ul>
        </section>

        <!-- TEMA 3 -->
        <section id="tema3">
            <h2>Tema 3: Las trampas del pensamiento</h2>

            <h3>Definición</h3>
            <div class="quote">"La mente recurre a atajos cognitivos que no siempre resultan eficaces. Dichos procesos se denominan sesgos cognitivos y prejuicios y condicionan la forma en que se interpreta la realidad."</div>

            <h3>Prejuicios</h3>
            <p>Ideas o juicios que se emiten sobre personas o situaciones sin conocerlas a fondo. Provienen de la cultura, los medios e incluso de la familia.</p>

            <h3>Heurísticos</h3>
            <p>Atenciones mentales que ayudan a simplificar la toma de decisiones. Aunque en muchos casos resultan útiles, lo que se gana en velocidad se pierde en precisión.</p>

            <h3>Tipos de sesgos</h3>
            <ul>
                <li><strong>Sesgo de disponibilidad:</strong> Se cree que algo es más frecuente solo porque se recuerda con facilidad.</li>
                <li><strong>Sesgo de confirmación:</strong> La mente se inclina a reafirmar lo que se considera correcto.</li>
                <li><strong>Efecto halo:</strong> La percepción sobre una persona se ve influenciada por una serie de rasgos.</li>
            </ul>

            <h3>Influencia social en las decisiones</h3>
            <ul>
                <li><strong>Efecto de grupo (Conformismo):</strong> Si todos opinan lo mismo, es probable que alguien se sume a esa postura para encajar.</li>
                <li><strong>Efecto espectador:</strong> En situaciones donde una persona necesita apoyo, la mayoría se abstiene de actuar.</li>
            </ul>
        </section>

        <!-- TEMA 4 -->
        <section id="tema4">
            <h2>Tema 4: La lupa del pensamiento</h2>

            <h3>Definición de pensamiento crítico</h3>
            <div class="quote">"Una herramienta poderosa que impulsa el análisis de lo que se escucha, se lee o se observa en el entorno, con el fin de evitar caer con facilidad en engaños o ideas equivocadas."</div>
            <div class="concept">Imagina el cerebro como una linterna: cuando se utiliza el pensamiento crítico, se dirige esa luz para ver con claridad lo que verdaderamente sucede.</div>

            <h3>Metacognición</h3>
            <p>Pensar sobre cómo piensas. Pregúntate cuáles emociones intervienen, si estás buscando solo datos que confirmen lo que ya crees, o si subestimas la complejidad del tema.</p>

            <h3>Elementos del pensamiento crítico</h3>
            <ul>
                <li><strong>Propósito:</strong> Todo pensamiento posee una intención: resolver un problema, comprender una situación o tomar una decisión.</li>
                <li><strong>Preguntas:</strong> Cuestionar por qué, quién, cómo, para qué o qué pasaría si abre una ventana a nuevas ideas.</li>
                <li><strong>Supuestos:</strong> Una creencia que se asume sin un análisis previo. El pensamiento crítico exige examinar esas creencias ocultas.</li>
                <li><strong>Fuentes confiables:</strong> Evalúa la calidad con criterios de autoridad, actualidad, evidencia y propósito.</li>
            </ul>

            <h3>Estructura del razonamiento</h3>
            <ul>
                <li><strong>Premisa:</strong> Una afirmación que sirve como base o evidencia.</li>
                <li><strong>Argumento:</strong> La unión de premisas y una conclusión.</li>
                <li><strong>Conclusión:</strong> La idea final que aparece después de "por lo tanto", "en consecuencia", etc.</li>
            </ul>

            <h3>Tácticas de análisis</h3>
            <ul>
                <li><strong>Método de los 5 porqués:</strong> Preguntar "¿por qué?" cinco veces seguidas.</li>
                <li><strong>Mapa argumentativo:</strong> Representar gráficamente premisas y conclusiones con flechas.</li>
            </ul>
        </section>

        <!-- TEMA 5 -->
        <section id="tema5">
            <h2>Tema 5: Detectives del lenguaje</h2>

            <h3>Lenguaje manipulador y falacias</h3>
            <div class="quote">"No siempre se basa en la lógica, sino en las emociones. Se presenta cuando una persona intenta convencer apelando al miedo, la culpa o la presión social."</div>

            <h3>Tipos de falacias</h3>
            <ul>
                <li><strong>Ad hominem:</strong> Atacar a la persona en lugar de sus ideas.</li>
                <li><strong>Hombre de paja:</strong> Distorsionar el argumento del oponente para hacerlo más fácil de atacar.</li>
                <li><strong>Falsa causa:</strong> Atribuir una relación entre dos hechos sin evidencia.</li>
                <li><strong>Autoridad:</strong> "Esto es verdad porque lo dijo cierto influencer".</li>
            </ul>

            <h3>Influencia de medios y redes sociales</h3>
            <ul>
                <li><strong>Publicidad:</strong> Rara vez expresa la verdad completa. La clave es hacer creer que se necesita algo para ser mejor o más aceptado.</li>
                <li><strong>Identidad digital:</strong> La versión de uno mismo en línea no siempre coincide con la realidad.</li>
                <li><strong>Algoritmos y burbujas:</strong> Muestran contenido similar al que ya se consume, creando una burbuja informativa.</li>
                <li><strong>Mecanismos de recompensa:</strong> Las plataformas activan la dopamina, lo que puede derivar en adicción digital.</li>
            </ul>

            <h3>Herramientas de protección</h3>
            <ul>
                <li><strong>Pausa racional:</strong> Desarrollar un "detector de emociones forzadas".</li>
                <li><strong>Cuestionamiento:</strong> "¿Esto es real o está editado?", "¿qué desean que sienta?"</li>
                <li><strong>Detox digital:</strong> Tomar descansos, buscar cuentas que aporten información valiosa.</li>
            </ul>
        </section>

        <!-- TEMA 6 -->
        <section id="tema6">
            <h2>Tema 6: Argumenta sin pelear</h2>

            <h3>Claridad y escucha con apertura</h3>
            <p>Si se comunica con seguridad, se utiliza un lenguaje claro y se explica cómo y por qué la propuesta puede funcionar, existe mayor posibilidad de que todos presten atención.</p>
            <div class="concept">Escuchar con apertura significa dejar de pensar en la respuesta mientras la otra persona expresa sus ideas y procurar comprender su punto de vista.</div>

            <h3>Validación</h3>
            <p>La comunicación no se trata solo de transmitir, sino de asegurarse de que el mensaje fue comprendido como se pretendía. Validar la interpretación del otro evita malentendidos.</p>

            <h3>Lenguaje no verbal</h3>
            <div class="quote">"Más del 50% de lo que se comunica no requiere palabras. El lenguaje corporal debe coincidir con el mensaje verbal para evitar contradicciones."</div>

            <h3>Reglas del diálogo crítico y empático</h3>
            <ul>
                <li><strong>Equilibrio:</strong> El diálogo parte del reconocimiento de que toda conversación tiene dimensiones racional y emocional.</li>
                <li><strong>El objetivo:</strong> No es convencer, sino entender y cooperar.</li>
                <li><strong>Filtros:</strong> ¿Es verdadero?, ¿es necesario?, ¿es respetuoso?</li>
            </ul>

            <h3>Comunicación asertiva</h3>
            <div class="concept">Aquella en la que existe un equilibrio entre la agresividad y la falta de afirmación, integrando el respeto por sí mismo y por los demás.</div>
        </section>

        <!-- TEMA 7 -->
        <section id="tema7">
            <h2>Tema 7: Pensamiento crítico en la era digital</h2>

            <h3>Identificación de información falsa</h3>
            <div class="quote">"El primer paso consiste en dudar de todo lo que se observa, incluidos los titulares exagerados o cargados de emoción."</div>

            <h3>Verificación de fuentes</h3>
            <p>Investigar la fuente, buscar medios reconocidos, revisar si otros sitios también lo publican e inspeccionar si incluyen datos verificables.</p>

            <h3>Análisis de multimedia</h3>
            <p>Examinar con cuidado imágenes y videos. Una fotografía puede estar fuera de contexto o manipulada. Existen aplicaciones para verificar si una imagen ha sido modificada.</p>

            <h3>Dinámicas de las redes sociales</h3>
            <ul>
                <li><strong>Burbujas informativas:</strong> Los algoritmos muestran contenido que refuerza las propias opiniones.</li>
                <li><strong>Sesgo de confirmación:</strong> A veces se cree o comparte información solo porque coincide con lo que se piensa.</li>
                <li><strong>Vulnerabilidad:</strong> Los menores son un público vulnerable con efectos negativos como ansiedad, depresión e insomnio.</li>
            </ul>

            <h3>Criterios para evaluar contenido</h3>
            <ul>
                <li><strong>Autoría:</strong> ¿Quién está detrás de la publicación?</li>
                <li><strong>Recursos del mensaje:</strong> Lenguaje exagerado, mayúsculas, emojis en exceso.</li>
                <li><strong>Intencionalidad:</strong> ¿Busca informar, vender, manipular o generar temor?</li>
                <li><strong>Temporalidad:</strong> Revisar la fecha y lugar del acontecimiento.</li>
            </ul>

            <h3>Responsabilidad digital</h3>
            <p>Antes de compartir, verificar. Mantener equilibrio respecto al tiempo de exposición en redes sociales.</p>
        </section>

        <!-- TEMA 8 -->
        <section id="tema8">
            <h2>Tema 8: Opinión vs. conocimiento</h2>

            <h3>Diferencias</h3>
            <ul>
                <li><strong>Creer:</strong> Aceptar algo como verdadero sin prueba definitiva. Se asocia con lo subjetivo.</li>
                <li><strong>Saber:</strong> Tener razones o hechos que confirmen la certeza de algo. Requiere un proceso racional y verificable.</li>
                <li><strong>Argumentar:</strong> Explicar por qué se piensa algo, utilizando razonamientos lógicos, datos o ejemplos.</li>
            </ul>

            <h3>Cuándo opinar y cuándo no</h3>
            <p><strong>Valor de la opinión:</strong> Las opiniones resultan valiosas cuando surgen del conocimiento, la empatía y la reflexión.</p>
            <div class="concept">Una opinión bien formada parte del análisis, la escucha y el respeto por las perspectivas ajenas.</div>

            <h3>Cuándo callar</h3>
            <ul>
                <li>Cuando no se domina el tema</li>
                <li>Cuando pueden reforzar estereotipos o prejuicios</li>
            </ul>
            <div class="quote">"El silencio no siempre representa indiferencia; muchas veces significa respeto, escucha activa o reflexión."</div>

            <h3>La voz necesaria</h3>
            <p>Presenciar una injusticia convierte la opinión en una necesidad. Opinar se transforma en un acto de responsabilidad y solidaridad.</p>
        </section>

        <!-- TEMA 9 -->
        <section id="tema9">
            <h2>Tema 9: Elegir bien</h2>

            <h3>Uso del pensamiento crítico en decisiones</h3>
            <div class="concept">Constituye una habilidad práctica que permite analizar situaciones, cuestionar la información y elegir con mayor discernimiento.</div>

            <h3>Proceso de análisis</h3>
            <p>Implica formular preguntas, investigar, comparar opciones y anticipar consecuencias.</p>
            <div class="quote">"Detenerse a analizar, contrastar y comprender se convierte en un acto de madurez intelectual."</div>

            <h3>Impacto profesional</h3>
            <p>Un trabajador que analiza alternativas, busca evidencias y fundamenta sus decisiones en datos concretos se convierte en un colaborador valioso.</p>

            <h3>Evaluación de consecuencias, valores y contexto</h3>
            <ul>
                <li><strong>Más allá del impulso:</strong> Evaluar las consecuencias, considerar los valores personales y analizar el contexto.</li>
                <li><strong>Valores e Identidad:</strong> Los valores no deben asumirse como normas fijas, sino como principios que se construyen con el tiempo.</li>
                <li><strong>Presión Social:</strong> Aprender a resistirla es parte del desarrollo del pensamiento crítico.</li>
                <li><strong>Contexto:</strong> Analizar el escenario antes de actuar para adaptar las decisiones.</li>
            </ul>
        </section>

        <!-- TEMA 10 -->
        <section id="tema10">
            <h2>Tema 10: Pensar para actuar</h2>

            <h3>Pensamiento crítico y entorno</h3>
            <div class="concept">Una habilidad que permite analizar, cuestionar y entender mejor lo que ocurre antes de llegar a una conclusión o actuar.</div>

            <h3>Identificación de problemas</h3>
            <p>No se trata de quejarse, sino de observar: ¿qué cosas podrían mejorarse?, ¿existen injusticias que se han normalizado?</p>

            <h3>Solidaridad</h3>
            <div class="quote">"Exige un grado mayor de conciencia, donde se reconoce que los seres humanos comparten un entorno del cual se deben hacer responsables."</div>

            <h3>De la queja a la acción</h3>
            <ul>
                <li><strong>La clave:</strong> Pasar de la queja a una acción informada y bien considerada.</li>
                <li><strong>Compromiso social:</strong> A veces basta con modificar hábitos e inspirar a otros.</li>
                <li><strong>Esfuerzo colectivo:</strong> La acción informada se fortalece cuando se convierte en un esfuerzo colectivo.</li>
                <li><strong>Aprendizaje del error:</strong> Equivocarse no significa fracasar, es parte de crecer.</li>
            </ul>

            <h3>Ocio educativo y competencias</h3>
            <p>Cuando los jóvenes participan activamente en la solución de problemas, desarrollan habilidades que se reflejan en otros ámbitos de su vida.</p>
        </section>

        <!-- TEMA 11 -->
        <section id="tema11">
            <h2>Tema 11: El poder de una mente ética</h2>

            <h3>La unión necesaria</h3>
            <div class="quote">"La verdadera fuerza de una mente responsable no solo radica en examinar y cuestionar, sino también en actuar con ética."</div>

            <h3>El papel de la ética</h3>
            <p>Conjunto de principios que rigen la conducta humana y resulta esencial para el adecuado desarrollo de una sociedad justa y equitativa.</p>
            <div class="concept">La ética y el pensamiento crítico funcionan como un equipo: uno analiza las opciones; el otro valora las consecuencias.</div>

            <h3>Dilemas y razonamiento ético</h3>
            <p><strong>¿Qué es un dilema ético?</strong> Cuando hay más de una alternativa posible, pero cada una implica resultados morales importantes.</p>
            <div class="quote">"Una mente ética no requiere que otros la vigilen para hacer lo justo; quien actúa así lo hace por compromiso con sus valores y principios."</div>

            <h3>Preguntas clave</h3>
            <ul>
                <li>¿Esto beneficia o afecta a alguien?</li>
                <li>¿Qué pasaría con el mundo si todos actuaran igual?</li>
                <li>¿Se está siendo honesto con uno mismo?</li>
            </ul>

            <h3>Impacto social y personal</h3>
            <ul>
                <li><strong>Construcción del carácter:</strong> Las decisiones pequeñas construyen la persona que uno llega a ser.</li>
                <li><strong>Ciudadanía responsable:</strong> La sociedad requiere personas éticas que busquen la justicia y la empatía.</li>
                <li><strong>Sentido de pertenencia:</strong> Cada persona posee la posibilidad de aportar sus talentos para mejorar.</li>
            </ul>
        </section>

        <!-- TEMA 12 -->
        <section id="tema12">
            <h2>Tema 12: Construyendo mi identidad como pensador crítico</h2>

            <h3>¿Qué es ser un pensador crítico hoy?</h3>
            <div class="quote">"No se trata de estar en contra solo porque sí, significa tener la capacidad de analizar los sucesos desde diferentes puntos de vista, identificar errores o manipulación en la información y sustentar las propias opiniones con explicaciones sólidas."</div>

            <h3>Responsabilidad digital</h3>
            <p>Compartir información dudosa puede causar daño. Una persona comienza a convertirse en un individuo más responsable al verificar fuentes antes de dar clic en "compartir".</p>

            <h3>Impacto de la inmediatez</h3>
            <p>Se publica contenido que puede evadir cualquier filtro de calidad, contraste o veracidad.</p>

            <h3>Autonomía intelectual y responsabilidad</h3>
            <ul>
                <li><strong>Pensar por uno mismo:</strong> La capacidad de pensar sin depender de lo que otros expresan.</li>
                <li><strong>Metacognición:</strong> Procesos de personas pensantes y reflexivas.</li>
                <li><strong>Reconocimiento de sesgos:</strong> Reconocer los propios sesgos, prejuicios y limitaciones.</li>
            </ul>

            <h3>El compromiso personal</h3>
            <div class="concept">Actuar con responsabilidad implica reconocer que cada elección conlleva consecuencias y que la autonomía no significa hacer lo que se quiera sin medir el efecto en los demás.</div>
            <p><strong>En el ámbito escolar:</strong> Se refleja cuando se realizan trabajos sin recurrir a la copia, fortaleciendo la confianza en las propias capacidades.</p>
        </section>
    </main>

    <footer>
        <p>Proyecto de Pensamiento Crítico - 12 Temas</p>
    </footer>

    <a href="#" class="back-to-top">↑</a>

</body>
</html>
