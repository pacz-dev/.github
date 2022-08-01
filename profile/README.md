``` ts
const name: string = 'pacz-dev';

class About extends Us {
    function getOrganizationInfo() {
        return {
            founded: 2022,
            owner: 'philipp-kremer',
            mission: 'contribute open-source projects from frontend to backend'
        }
    }

    function getAllMembers() {
        return [
            'philipp-kremer'
        ]
    }
}
```