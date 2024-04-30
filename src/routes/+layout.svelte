<script>
import "../app.css";
import * as Tabs from "$lib/components/ui/tabs/index.js";
import * as Card from "$lib/components/ui/card/index.js";
import ProcedurePage from "../customcomponents/procedure.svelte";
import HomePage from "../customcomponents/home.svelte";
import HistoricalPrecedentPage from "../customcomponents/historical-precedent.svelte";
import SolutionPage from "../customcomponents/solution.svelte";
import EvidencePage from "../customcomponents/evidence.svelte";
import ArtPage from "../customcomponents/art.svelte";


</script>

<html class="dark" lang="en">
    <body>
        <!-- Not best practice - uses tab list to switch between pages, each page is a component -->
        <nav>
            <Tabs.Root value="HomeTab" class="w-[90%]">
                <Tabs.List class="grid w-full grid-cols-6">
                    <Tabs.Trigger value="HomeTab">Home</Tabs.Trigger>
                    <Tabs.Trigger value="historical-precedent">Historical Precedent</Tabs.Trigger>
                    <Tabs.Trigger value="procedure">Procedure</Tabs.Trigger>
                    <Tabs.Trigger value="solution">Solution</Tabs.Trigger>
                    <Tabs.Trigger value="evidence">Evidence</Tabs.Trigger>
                    <Tabs.Trigger value="art">Art</Tabs.Trigger>
                </Tabs.List>
                <Tabs.Content value="HomeTab">
                    <Card.Content class="flex justify-center w-full h-auto">
                        <div class="flex items-center content-center w-11/12 h-11/12">
                            <Card.Root value="HomeCard" class="w-full h-full">
                                <HomePage />
                            </Card.Root>
                        </div>
                    </Card.Content>
                </Tabs.Content>
                <Tabs.Content value="historical-precedent">
                    <Card.Content class="flex justify-center w-full h-auto">
                        <div class="flex items-center justify-center w-11/12 h-11/12">
                            <Card.Root value="ProcedureCard" class="w-full h-full">
                                <HistoricalPrecedentPage />
                            </Card.Root>
                        </div>
                    </Card.Content>
                </Tabs.Content>
                <Tabs.Content value="procedure">
                    <Card.Content class="flex justify-center w-full h-auto">
                        <div class="flex items-center justify-center w-11/12 h-11/12">
                            <Card.Root value="ProcedureCard" class="w-full h-full">
                                <ProcedurePage />
                            </Card.Root>
                        </div>
                    </Card.Content>
                </Tabs.Content>
                <Tabs.Content value="solution">
                    <Card.Content class="flex justify-center w-full h-auto">
                        <div class="flex items-center justify-center w-11/12 h-11/12">
                            <Card.Root value="ProcedureCard" class="w-full h-full">
                                <SolutionPage />
                            </Card.Root>
                        </div>
                    </Card.Content>
                </Tabs.Content>
                <Tabs.Content value="evidence">
                    <Card.Content class="flex justify-center w-full h-auto">
                        <div class="flex items-center justify-center w-11/12 h-11/12">
                            <Card.Root value="ProcedureCard" class="w-full h-full">
                                <EvidencePage />
                            </Card.Root>
                        </div>
                    </Card.Content>
                </Tabs.Content>
                <Tabs.Content value="art">
                    <Card.Content class="flex justify-center w-full h-auto">
                        <div class="flex items-center justify-center w-11/12 h-11/12">
                            <Card.Root value="ProcedureCard" class="w-full h-full">
                                <ArtPage />
                            </Card.Root>
                        </div>
                    </Card.Content>
                </Tabs.Content>
                
            </Tabs.Root>
        </nav>
    </body>
</html>

<style>
    body {
        width: 100% !important;
        height: 100% !important; 
        margin: 0 !important;
        background-color: #1B1B1B; 
        /* 1B1B1B or 010409 */
    }
    nav{
        display: flex;
        justify-content: center;
        gap: 1%;
        margin-top:10px;
        width: 100%;
        height: 100%;
    }
</style>

<!-- <slot></slot> -->