![1](https://user-images.githubusercontent.com/66241934/83455742-b80d9380-a45e-11ea-86e8-b48ea65693e9.jpg)
![2](https://user-images.githubusercontent.com/66241934/83455744-b80d9380-a45e-11ea-8564-859d3e364f64.jpg)
![3](https://user-images.githubusercontent.com/66241934/83455745-b8a62a00-a45e-11ea-9b8b-202a644b1800.jpg)
![4](https://user-images.githubusercontent.com/66241934/83455747-b8a62a00-a45e-11ea-8764-22d35f39ce76.jpg)
![5](https://user-images.githubusercontent.com/66241934/83455749-b93ec080-a45e-11ea-8118-09aa52028bb2.jpg)

![6](https://user-images.githubusercontent.com/66241934/83455731-b5ab3980-a45e-11ea-96c4-4dc9fff4dd4a.jpg)
![7](https://user-images.githubusercontent.com/66241934/83455733-b6dc6680-a45e-11ea-8363-b2ab18b975c9.jpg)
![8](https://user-images.githubusercontent.com/66241934/83455736-b774fd00-a45e-11ea-84d5-0f08f32bdf17.jpg)
![9](https://user-images.githubusercontent.com/66241934/83455740-b774fd00-a45e-11ea-85a1-f8a1bd080552.jpg)


[bd_practica4.txt](https://github.com/Pedroshky/TE2_practica4/files/4713499/bd_practica4.txt)




# TE2_practica4-- phpMyAdmin SQL Dump



-- version 4.9.1
-- https://www.phpmyadmin.net/
--
-- Servidor: 127.0.0.1
-- Tiempo de generación: 01-06-2020 a las 10:07:34
-- Versión del servidor: 10.4.8-MariaDB
-- Versión de PHP: 7.3.11

SET SQL_MODE = "NO_AUTO_VALUE_ON_ZERO";
SET AUTOCOMMIT = 0;
START TRANSACTION;
SET time_zone = "+00:00";


/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;

--
-- Base de datos: `bd_practica4`
--

-- --------------------------------------------------------

--
-- Estructura de tabla para la tabla `blogs`
--

CREATE TABLE `blogs` (
  `IdB` int(11) NOT NULL,
  `NombreU` varchar(50) COLLATE utf8_spanish_ci NOT NULL DEFAULT '0',
  `NombreB` varchar(500) COLLATE utf8_spanish_ci NOT NULL DEFAULT '0',
  `ContenidoB` varchar(5000) COLLATE utf8_spanish_ci NOT NULL DEFAULT '0',
  `FechaB` varchar(50) COLLATE utf8_spanish_ci NOT NULL DEFAULT ''
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COLLATE=utf8_spanish_ci;

--
-- Volcado de datos para la tabla `blogs`
--

INSERT INTO `blogs` (`IdB`, `NombreU`, `NombreB`, `ContenidoB`, `FechaB`) VALUES
(1, 'across', 'Coronavirus y personas mayores: un grupo altamente vulnerable', 'Los adultos mayores son uno de los mayores grupos de riesgo frente al avance del coronavirus, presentando la mayor tasa de fatalidad en diversos paÃ­ses. EntÃ©rate sobre los recursos y materiales que ofrecemos para orientar los cuidados y las polÃ­ticas pÃºblicas sobre envejecimiento y atenciÃ³n a la dependencia en los paÃ­ses de la regiÃ³n.  Residencias de adultos mayores: peligrosos focos de contagio Desde el inicio de la epidemia del coronavirus, se comprobÃ³ que el grupo de edad mÃ¡s vulnerable son los adultos mayores. Estos enfrentan un mayor riesgo por su inmunidad reducida y porque poseen una mayor probabilidad de padecer enfermedades crÃ³nicas/comorbilidades, como la diabetes, el cÃ¡ncer o la hipertensiÃ³n. En caso de contraer el virus, la probabilidad de sufrir complicaciones severas e incluso la muerte es considerable. En esta situaciÃ³n, las residencias para adultos mayores representan un foco de contagios potenciales muy peligroso, de hecho en  paÃ­ses como EspaÃ±a y Estados Unidos, estas residencias  presentan mÃºltiples contagios seguidos de muerte de sus residentes, y los mayores de 60 aÃ±os representan la mayor tasa de fatalidad por COVID-19 en Italia, EspaÃ±a y Estados Unidos.', '12/5/1999'),
(3, 'across', 'A lavarse las manos.Un estudio demuestra que la economia en los buenos habitos de higiene previene el coronavirus ', 'MantÃÂ©ngase al dÃÂ­a de la informaciÃÂ³n mÃÂ¡s reciente sobre el brote de COVID-19, a la que puede acceder en el sitio web de la OMS y a travÃÂ©s de las autoridades de salud pÃÂºblica pertinentes a nivel nacional y local. La COVID-19 sigue afectando principalmente a la poblaciÃÂ³n de China, aunque se han producido brotes en otros paÃÂ­ses. La mayorÃÂ­a de las personas que se infectan padecen una enfermedad leve y se recuperan, pero en otros casos puede ser mÃÂ¡s grave. Cuide su salud y proteja a los demÃÂ¡s a travÃÂ©s de las siguientes medidas:  LÃÂ¡vese las manos frecuentemente LÃÂ¡vese las manos con frecuencia con un desinfectante de manos a base de alcohol o con agua y jabÃÂ³n.  ÃÂ¿Por quÃÂ©? Lavarse las manos con un desinfectante a base de alcohol o con agua y jabÃÂ³n mata el virus si este estÃÂ¡ en sus manos.  Adopte medidas de higiene respiratoria Al toser o estornudar, cÃÂºbrase la boca y la nariz con el codo flexionado o con un paÃÂ±uelo; tire el paÃÂ±uelo inmediatamente y lÃÂ¡vese las manos con un desinfectante de manos a base de alcohol, o con agua y jabÃÂ³n.  ÃÂ¿Por quÃÂ©? Al cubrir la boca y la nariz durante la tos o el estornudo se evita la propagaciÃÂ³n de gÃÂ©rmenes y virus. Si usted estornuda o tose cubriÃÂ©ndose con las manos puede contaminar los objetos o las personas a los que toque.  Mantenga el distanciamiento social Mantenga al menos 1 metro (3 pies) de distancia entre usted y las demÃÂ¡s personas, particularmente aquellas que tosan, estornuden y tengan fiebre.  ÃÂ¿Por quÃÂ©? Cuando alguien con una enfermedad respiratoria, como la infecciÃÂ³n por el 2019-nCoV, tose o estornuda, proyecta pequeÃÂ±as gotÃÂ­culas que contienen el virus. Si estÃÂ¡ demasiado cerca, puede inhalar el virus.', '12/5/2000');

-- --------------------------------------------------------

--
-- Estructura de tabla para la tabla `usuarios`
--

CREATE TABLE `usuarios` (
  `IdU` int(11) NOT NULL,
  `NombreU` varchar(50) COLLATE utf8_spanish_ci NOT NULL DEFAULT '0',
  `ContraseniaU` varchar(50) COLLATE utf8_spanish_ci NOT NULL DEFAULT '0'
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COLLATE=utf8_spanish_ci;

--
-- Volcado de datos para la tabla `usuarios`
--

INSERT INTO `usuarios` (`IdU`, `NombreU`, `ContraseniaU`) VALUES
(1, 'across', '123'),
(3, 'toto', '123');

--
-- Índices para tablas volcadas
--

--
-- Indices de la tabla `blogs`
--
ALTER TABLE `blogs`
  ADD PRIMARY KEY (`IdB`),
  ADD KEY `FK_blogs_usuarios` (`NombreU`);

--
-- Indices de la tabla `usuarios`
--
ALTER TABLE `usuarios`
  ADD PRIMARY KEY (`IdU`),
  ADD UNIQUE KEY `IdU` (`IdU`),
  ADD UNIQUE KEY `NombreU` (`NombreU`);

--
-- AUTO_INCREMENT de las tablas volcadas
--

--
-- AUTO_INCREMENT de la tabla `blogs`
--
ALTER TABLE `blogs`
  MODIFY `IdB` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=4;

--
-- AUTO_INCREMENT de la tabla `usuarios`
--
ALTER TABLE `usuarios`
  MODIFY `IdU` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=4;

--
-- Restricciones para tablas volcadas
--

--
-- Filtros para la tabla `blogs`
--
ALTER TABLE `blogs`
  ADD CONSTRAINT `FK_blogs_usuarios` FOREIGN KEY (`NombreU`) REFERENCES `usuarios` (`NombreU`);
COMMIT;

/*!40101 SET CHARACTER_SET_CLIENT=@OLD_CHARACTER_SET_CLIENT */;
/*!40101 SET CHARACTER_SET_RESULTS=@OLD_CHARACTER_SET_RESULTS */;
/*!40101 SET COLLATION_CONNECTION=@OLD_COLLATION_CONNECTION */;
