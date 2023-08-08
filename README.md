# 🏋️ About Me:
🌱 I’m currently learning R3F, Blender and 3D modelling<br><br>🤝 I’m looking for help with Three.js and Blender<br><br>👨‍💻 All of my projects are available at https://profile-card-github.web.app/<br><br>💬 Ask me about Building cutting-edge websites with React, GSAP, and Three.js—because who needs sleep, social life, or a semblance of sanity when you can obsess over pixels and semicolons? But hey, at least my GitHub commit graph looks impressive, even if my personal life suffers!<br><br>📫 How to reach me manaslaud@hotmail.com<br><br>📄 Know about my experiences https://www.linkedin.com/in/manas-laud-5183a5254/<br><br>⚡ Fun fact I do touch grass
```javascript
import React, { useEffect, useRef } from 'react';
import * as Three from 'three';
const Developer: React.FC = () => {
  const canvasRef = useRef<HTMLCanvasElement>(null);
  useEffect(() => {
    const renderer = new Three.WebGLRenderer({ canvas: canvasRef.current });
    renderer.setSize(window.innerWidth, window.innerHeight);
    const scene = new Three.Scene();
    const camera = new Three.PerspectiveCamera(75, window.innerWidth / window.innerHeight, 0.1, 1000);
    camera.position.z = 5;
    const cube = new Three.Mesh(new Three.BoxGeometry(), new Three.MeshBasicMaterial({ color: 'skyblue' }));
    scene.add(cube);
    const animate = () => {
      requestAnimationFrame(animate);
      cube.rotation.y += 0.01;
      renderer.render(scene, camera);
    };
    animate();
  }, []);
  return <canvas ref={canvasRef} />;
};
export default Developer;
```

## 🌐 Socials:
[![Behance](https://img.shields.io/badge/Behance-1769ff?logo=behance&logoColor=white)](https://behance.net/manaslaud) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/manaslaud) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/manaslaud) 

# 💻 Tech Stack:
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white) 	![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Dribbble](https://img.shields.io/badge/Dribbble-EA4C89?style=for-the-badge&logo=dribbble&logoColor=white) ![Adobe Illustrator](https://img.shields.io/badge/adobeillustrator-%23FF9A00.svg?style=for-the-badge&logo=adobeillustrator&logoColor=white)
# 📊 GitHub Stats:

![](https://github-readme-streak-stats.herokuapp.com/?user=manaslaud&theme=vue-dark&hide_border=false)<br/>

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=manaslaud&theme=radical&no-frame=true&no-bg=false&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)



<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
