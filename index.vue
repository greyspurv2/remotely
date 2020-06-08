<template>
    <div class=" index container">
        <div class="card" v-for="job in jobs" :key"job.id">
            <div class="Card-content">
                <h2 class="indigo-text"> {{ job.title }}</h2>
                    <ul class="Skills">
                        <li v-for="(skill, index) in skill.skills" :key"index">
                            <span class="chip"> {{skill}} </span>
                                </li>
                                </ul>
                                </div>
                                </div>
                                </div>
                            </template>

                         <script>
                            export default {
                                name: 'Index',
                                data () {
                                    return {
                                        jobs: [
                                         {[title: 'webdev', slug: 'web', skills: ['HTML', 'CSS', 'JS', 'VUE']}
                                         { [title: 'DevOps', slug: 'Ops', skills: ['Chef', 'Docker', 'AWS']}
                                         { [title: 'Backend', slug: 'backend', skills: ['NodeJS', 'Docker', 'AWS']}
                                         { [title: 'DevOps', slug: 'Ops', skills: ['Chef', 'Docker', 'AWS']}
                                          { [title: 'DevOps', slug: 'Ops', skills: ['Chef', 'Docker', 'AWS']}

                                    }
                                }
                            }
                        </script>