<template>
    <v-app>
        <v-main>
            <v-container>
                <v-row>
                    <v-col
                        cols="12"
                    >
                        <v-text-field
                            label="Student Number"
                            variant="outlined"
                        ></v-text-field>
                    </v-col>
                
                    <v-col
                        cols="12"
                        md="4"
                    >
                        <v-text-field
                            label="Last Name"
                            variant="outlined"
                        ></v-text-field>    
                    </v-col>

                    <v-col
                        cols="12"
                        md="4"
                    >
                        <v-text-field
                            label="First Name"
                            variant="outlined"
                        ></v-text-field>    
                    </v-col>

                    <v-col
                        cols="12"
                        md="4"
                    >
                        <v-text-field
                            label="Last Name"
                            variant="outlined"
                        ></v-text-field>    
                    </v-col>
                    
                    <v-col
                        cols="12"
                        md="4"
                    >
                    <v-combobox
                    label="Course"
                    :items="['DCT', 'BSCS']"
                    ></v-combobox>
                    </v-col>

                    <v-col
                        cols="12"
                        md="4"
                    >
                    <v-combobox
                    label="Year"
                    :items="['1st year', '2nd year', '3rd year', '4th year']"
                    ></v-combobox>
                    </v-col>

                    <v-col
                        cols="12"
                        md="4"
                    >
                    <v-combobox
                    label="Section"
                    :items="['A', 'B', 'C', 'D']"
                    ></v-combobox>
                    </v-col>

                    <v-col
                        cols="12"
                        md="4"
                    >
                        <v-text-field
                            label="Address"
                            variant="outlined"
                        ></v-text-field>    
                    </v-col>

                    <v-col
                        cols="12"
                        md="4"
                    >
                        <v-text-field
                            label="Contact Number"
                            variant="outlined"
                        ></v-text-field>    
                    </v-col>

                    <v-col
                        cols="12"
                        md="4"
                    >
                    <v-combobox
                    label="Gender"
                    :items="['Male', 'Female', 'LGBTQ']"
                    ></v-combobox>
                    </v-col>

                </v-row>
            </v-container>
        </v-main>
    </v-app>
</template>