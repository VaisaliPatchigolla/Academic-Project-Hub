# projectfolder

// // Schema and Model for Project1
// const projectSchema1 = new mongoose.Schema({
//     title: String,
//     technologies: [String],
//     description: String
// });

// const Project1 = mongoose.model('Project1', projectSchema1);

// // Schema and Model for Project2
// const projectSchema2 = new mongoose.Schema({
//     title: String,
//     technologies: [String],
//     description: String
// });

// const Project2 = mongoose.model('Project2', projectSchema2);

// // Schema and Model for Project3
// const projectSchema3 = new mongoose.Schema({
//     title: String,
//     technologies: [String],
//     description: String
// });

// const Project3 = mongoose.model('Project3', projectSchema3);
// // Route to handle project data submission for Project1
// app.post('/submitData1', async (req, res) => {
//     try {
//         // Extract project data from request body
//         const { title, technologies, description } = req.body;

//         // Create new project instance for Project1
//         const newProject = new Project1({
//             title,
//             technologies,
//             description
//         });

//         // Save the project data to the database
//         await newProject.save();

//         // Respond with success message
//         res.send('<script>alert("Project Description added successfully"); window.location.href = "/file_upload1.html"; </script>');
//     } catch (error) {
//         console.error(error);
//         res.status(500).send('Internal Server Error');
//     }
// });

// // Route to handle project data submission for Project2
// app.post('/submitData2', async (req, res) => {
//     try {
//         // Extract project data from request body
//         const { title, technologies, description } = req.body;

//         // Create new project instance for Project2
//         const newProject = new Project2({
//             title,
//             technologies,
//             description
//         });

//         // Save the project data to the database
//         await newProject.save();

//         // Respond with success message
//         res.send('<script>alert("Project Description added successfully"); window.location.href = "/file_upload2.html"; </script>');
//     } catch (error) {
//         console.error(error);
//         res.status(500).send('Internal Server Error');
//     }
// });

// // Route to handle project data submission for Project3
// app.post('/submitData3', async (req, res) => {
//     try {
//         // Extract project data from request body
//         const { title, technologies, description } = req.body;

//         // Create new project instance for Project3
//         const newProject = new Project3({
//             title,
//             technologies,
//             description
//         });

//         // Save the project data to the database
//         await newProject.save();

//         // Respond with success message
//         res.send('<script>alert("Project Description added successfully"); window.location.href = "/file_upload3.html"; </script>');
//     } catch (error) {
//         console.error(error);
//         res.status(500).send('Internal Server Error');
//     }
// });
