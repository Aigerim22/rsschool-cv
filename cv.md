# AIGERIM TAZHIBAY  
**Major**: *Information Systems*   
**Goal**: *Learn Web Development and to become competent Frontend Developer!*

### Contacts:
*Email: aika0822t@gmail.com   
Phone: +7(771) 335 07 76   
Github: github.com/Aigerim22*

### Education
**Nazarbayev Intellectual School** (*Taraz, Kazakhstan (Aug. 2013 - May 2018)*)
- Major: Physics & Chemistry 

**Kazakh-British Technical University**(*Almaty, Kazakhstan Aug.18-Expected Jun.2021*)
 - B.S. in Information Systems, GPA: 3.64/4.0
 
 ### Personal/Soft Skills
-  Active listening skills: note-taking, organization, punctuality;
-  Interpersonal skills: adaptability, teamwork;
- Willingness to learn;

### Technical Skills
**Programming Languages**: C++,C#, Java, Python, Javascript, Typescript, HTML/CSS   
**Databases**: SQL, MySQL, PostgreSQL, SQLite   
**Frameworks**: Angular, React, Django   
**IDE's**: Visual Studio, Visual Studio Code, Eclipse, PyCharm, JetBrains DataGrip

###  Work Experience
I don't have an work experience, but I'm ready to learn and gain knowledge!
#### Experience (internships)
**Kazakh-British Technical University** *(Almaty, Kazakhstan (May. 2019 - August.2019)*   
Assistant in the project "Intelligent Search and Forecasting of Litigation" 
- Processing incoming data
- Markup of court documents(500 documents checked and marked)

### Code Examples
```
News.tsx
const initialState = {
  loading: true,
  error: "Success",
  images: [],
};
function reducer(state = initialState, action: Action) {
  switch (action.type) {
    case Actions.GET_DATA:
      return {
        loading: false,
        images: action.payload,
        error: "",
      };
    case Actions.NO_DATA:
      return {
        loading: false,
        images: [],
        error: "404!No data returned!",
      };
    default:
      return state;
  }
}
function Blog() {
  const [state, dispatch] = useReducer(reducer, initialState);

  useEffect(() => {
    axios
      .get(
        `${BASE_URL}?q=Часы&pageSize=10&from=2020-12-14&sortBy=popularity&apiKey=${API_KEY}`
      )
      .then((response) => {
        dispatch({ type: Actions.GET_DATA, payload: response.data.articles });
      })
      .catch((error) => {
        dispatch({ type: Actions.NO_DATA, payload: error });
      });
  }, []);

  return (
    <>
    ...
 ```
 
### Additional information
- Completion of Science and English Camp, Kuala Lumpur Malaysia, December 2019
- Completion of Nazarbayev Intellectual School with Red Certificate
- Won "Best Delegate" in Model United Nations held by KBTU Student organization
- Successfully passed IELTS exam and got 6.5/9 (Level B2)
- Participation in volunteer programs KBTU Day Almaty 2020, Creative Spark Higher Education Enterprise Program


**Digitalization office** *(Jun. 2020 -Aug. 2020)*   
Intern in the project "Inventory of information systems and audit of information security" Almaty, Kazakhstan 
- Introduction of advice on filling out questionnaires on the inventory of information systems: IP Survey,
- Defnition of data objects stored in information systems, Inspection of the Customer's IT infrastructure;

### University Projects
**Intranet - Student Management System**
- Creation of Intranet - Student Management System which concludes student/teacher actions as grading,
receiving marks, checking attendance etc.
- Used Java programming language and principles of OOP
- MySQL was used to store the entities

**Online-Shop**
- Creation of web application for customers to shop and purchase products online. The site includes selecting
products, search by categories, adding to cart selected products, see details etc.
- MySQL selected to store user data
- The front-end of project written in Angular Js, back-end by Django REST Framework


**Online-Shop2**
- Creation of web application for customers to shop and purchase products online. The site includes selecting
products, adding to cart selected products, added image gallery, search by queries, details of products.
- The project is written in React TS, backend is not developed.
- Used Context API, Redux, Axios, React hooks etc. in project.
Link: * [https://github.com/Aigerim22/REACT] (private)
