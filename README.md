import React from 'react';

const CV = () => {
  return (
    <div style={{ fontFamily: 'Arial, sans-serif', maxWidth: '800px', margin: '0 auto', padding: '20px' }}>
      <header style={{ textAlign: 'center', marginBottom: '50px' }}>
        <h1>Oday Hmydat</h1>
        <p>Koura District, Irbid, Jordan</p>
        <p>Email: <a href="mailto:odyhmydat@gmail.com">odyhmydat@gmail.com</a></p>
        <p>Phone: +962 780 545 668</p>
      </header>

      <section style={{ marginBottom: '30px' }}>
        <h2>Education</h2>
        <p>
          A student from the third cohort of Cybersecurity at Yarmouk University, expected to graduate in 2025.
        </p>
      </section>

      <section style={{ marginBottom: '30px' }}>
        <h2>Experience</h2>
        <ul>
          <li>
            <strong>Data Entry Assistant</strong> at Computer and Information Center, Yarmouk University.
          </li>
          <li>
            <strong>Problem Analyst</strong> at Computer Centre, resolving usage errors for students with issues such as incorrect passwords and university emails.
          </li>
          <li>
            Assisted students with personal emails used to access external university-related courses, such as Cisco courses.
          </li>
        </ul>
      </section>

      <section style={{ marginBottom: '30px' }}>
        <h2>Skills</h2>
        <p>Proficient in Microsoft Office, data analysis, and IT troubleshooting.</p>
      </section>

      <section style={{ marginBottom: '30px' }}>
        <h2>Achievements</h2>
        <p>
          Contributed to improving the data management system by 20% through implementing updates and new technologies.
        </p>
      </section>
    </div>
  );
};

export default CV;
