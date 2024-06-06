# TinDog Project

## Overview
TinDog is a web-based application designed to help dogs and their owners meet new and interesting dogs nearby. The project is built using HTML, CSS, and Bootstrap, ensuring a responsive and visually appealing design. 

## Key Features
- **User-Friendly Interface**: The app is designed to be extremely easy to use, even for dog owners who are not tech-savvy.
- **Elite Clientele**: TinDog boasts a wide variety of dogs, ensuring that every user can find the perfect match.
- **Money-Back Guarantee**: If users are not satisfied with the matches, they are guaranteed their money back.

## Text Content
- **Title Section**: 
  - Meet new and interesting dogs nearby.

- **Features Section**:
  - Easy to use.
    - So easy to use, even your dog could do it.
  - Elite Clientele.
    - We have all the dogs, the greatest dogs.
  - Guaranteed to work.
    - Find the love of your dog's life or your money back.

- **Testimonial Section**:
  - "I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof."
    - Pebbles, New York

- **Pricing Section**:
  - A Plan for Every Dog's Needs
  - Simple and affordable price plans for you and your dog.

  - **Chihuahua Plan**:
    - $0/mo
    - 5 Matches Per Day
    - 10 Messages Per Day
    - Unlimited App Usage

  - **Labrador Plan**:
    - $15/mo
    - Unlimited Matches
    - Unlimited Messages
    - Unlimited App Usage

  - **Mastiff Plan**:
    - $29/mo
    - Priority Listing
    - Unlimited Matches & Messages
    - Unlimited App Usage

## Bootstrap Components Used
To find out which Bootstrap components and snippets are used in this project, refer to the [Bootstrap snippets PDF](https://github.com/appbrewery/tindog/blob/main/Bootstrap-snippets.pdf).

## Installation and Usage
1. **Clone the repository**:
    ```bash
    git clone https://github.com/appbrewery/tindog.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd tindog
    ```
3. **Open `index.html` in your browser** to view the app.

## File Structure
- `index.html`: The main HTML file containing the structure of the web application.
- `style.css`: The CSS file for custom styles.
- `images/`: Directory containing all images used in the project.

## Custom CSS
- **Gradient Background**:
  ```css
  .gradient-background {
      background: linear-gradient(300deg, #00bfff, #ff4c68, #ef8172);
      background-size: 180% 180%;
      animation: gradient-animation 18s ease infinite;
  }
  
  @keyframes gradient-animation {
      0% {
          background-position: 0% 50%;
      }
      50% {
          background-position: 100% 50%;
      }
      100% {
          background-position: 0% 50%;
      }
  }
  ```

- **Icon Square**:
  ```css
  .icon-square {
      width: 3rem;
      height: 3rem;
      border-radius: 0.75rem;
  }
  ```

- **Profile Image**:
  ```css
  .profile-img {
      height: 100px;
      border-radius: 50%;
  }
  ```

## Contribution
Feel free to fork this project, submit issues and pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License. See the LICENSE file for details.
