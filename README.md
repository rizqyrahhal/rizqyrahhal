import React from 'react';

const ReadmeGenerator = ({ title, description, installation, usage }) => {
  return (
    <div>
      <h1>{title}</h1>
      <p>{description}</p>
      
      <h2>Installation</h2>
      <p>{installation}</p>
      
      <h2>Usage</h2>
      <p>{usage}</p>
    </div>
  );
};

export default ReadmeGenerator;
