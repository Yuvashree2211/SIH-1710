# Smart India Hackathon Workshop
# Date:26-10-2026
## Register Number: 212224040378
## Name: YUVASHREE R
## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea
SmartRail is a smart railway station navigation website that helps passengers easily find platforms, ticket counters, restrooms, food courts, waiting halls, lifts, and exits. It provides an interactive station map, shortest-route navigation, voice guidance, and accessible routes for elderly passengers and people with disabilities. QR codes can help passengers identify their starting location. The system also allows administrators to update station facilities and route information.

## Proposed Solution / Architecture Diagram
The proposed solution is a web-based navigation system that works on mobile phones, computers, and digital kiosks. Passengers can search for a facility, select their destination, and view step-by-step directions on an interactive station map. Voice guidance and wheelchair-friendly routes improve accessibility.

<img width="747" height="560" alt="image" src="https://github.com/user-attachments/assets/8af1c2f6-bd21-4b1e-9787-1df244f905ca" />


## Use Cases

1.Search for railway station facilities and locations.
2.View interactive maps and shortest routes to destinations.
3.Get step-by-step directions and voice guidance.
4.Find wheelchair-friendly routes using lifts and ramps.
5.Scan QR codes to identify the current starting location.
6.Allow administrators to update facility locations and route information.
7.Access the navigation website through mobile devices and digital kiosks.


## Technology Stack

<img width="632" height="427" alt="image" src="https://github.com/user-attachments/assets/922d6d8a-08a4-4814-81e0-fe82462c6d36" />

## Dependencies

1.Python 3.x and Flask.
2.HTML, CSS, and JavaScript development environment.
3.SQLite database for storing station and facility information.
4.Station floor maps with platform and facility locations.
5.Leaflet.js or a custom interactive map.
6.Dijkstra's algorithm for route calculation.
7.Browser support for voice guidance and QR scanning.
8.Internet connectivity for online deployment and externally hosted map resources, where required.
