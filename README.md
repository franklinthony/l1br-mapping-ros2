<h1 align="center">
    :robot: :world_map:
</h1>

<h1 align="center">
  Mapping with L1Br
</h1>
<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/franklinthony/l1br-ros2-mapping">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/franklinthony/l1br-ros2-mapping">
  
  <a href="https://github.com/franklinthony/l1br-ros2-mapping/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/franklinthony/l1br-ros2-mapping">
  </a>

  <a href="https://github.com/franklinthony/l1br-ros2-mapping/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/franklinthony/l1br-ros2-mapping">
  </a>
</p>

<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>
</p>

<br>

## 💻 Projeto

Foi desenvolvido como projeto da disciplina Robótica um pipeline para realizar o mapeamento, a localização e o controle de trajetória aplicados à otimização no mapeamento de um ambiente previamente repassado. 

## :grey_question: Como executar

Basta [clicar aqui](https://drive.google.com/drive/folders/1imoPEQZb_cDR7WrmB_l8wDuNbp8qPnyD), baixar os arquivos e executar os comandos a seguir. 

- Passo 1: ```source /opt/ros/humble/setup.bash``` 

- Passo 2: ```colcon build```

- Passo 3: ```cd install  & . setup.bash```

Obs.: Executar os comandos abaixo em terminais separados

- Passo 4: ```ros2 launch ugv_simulation world_launch.py```

- Passo 5: ```ros2 launch ugv_robots_description l1br_description_launch.py```

- Passo 6: ```ros2 launch ugv_navigation navigation.launch.py```

- Passo 7: ```ros2 launch slam_gmapping slam_gmapping.launch.py```
