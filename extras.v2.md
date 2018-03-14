








/v1/areas:
  get:
    headers:
        x-access-token:
          displayName: Web token
    responses:
      200:
        body:
          application/json:
            schema: !include schema/areas/model.array.json

  /page/{page}/limit/{limit}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/areas/model.array.json

  /{area_id}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/areas/model.json
    put:
      headers:
          x-access-token:
            displayName: Web token
      body:
        application/json:
          schema: !include schema/areas/model.post.json
      responses:
        200:
          body:
            application/json:
              schema: !include schema/areas/model.json
    delete:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/areas/model.json

/v1/atts:
  get:
    headers:
        x-access-token:
          displayName: Web token
    responses:
      200:
        body:
          application/json:
            schema: !include schema/atts/model.array.json

  /page/{page}/limit/{limit}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/atts/model.array.json

  /{att_id}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/atts/model.json
    put:
      headers:
          x-access-token:
            displayName: Web token
      body:
        application/json:
          schema: !include schema/atts/model.post.json
      responses:
        200:
          body:
            application/json:
              schema: !include schema/atts/model.json
    delete:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/atts/model.json

/v1/events:
  get:
    headers:
        x-access-token:
          displayName: Web token
    responses:
      200:
        body:
          application/json:
            schema: !include schema/events/model.array.json

  /page/{page}/limit/{limit}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/events/model.array.json

  /{event_id}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/events/model.json
    put:
      headers:
          x-access-token:
            displayName: Web token
      body:
        application/json:
          schema: !include schema/events/model.post.json
      responses:
        200:
          body:
            application/json:
              schema: !include schema/events/model.json
    delete:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/events/model.json

/v1/groups:
  get:
    headers:
        x-access-token:
          displayName: Web token
    responses:
      200:
        body:
          application/json:
            schema: !include schema/groups/model.array.json

  /page/{page}/limit/{limit}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/groups/model.array.json

  /{group_id}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/groups/model.json
    put:
      headers:
          x-access-token:
            displayName: Web token
      body:
        application/json:
          schema: !include schema/groups/model.post.json
      responses:
        200:
          body:
            application/json:
              schema: !include schema/groups/model.json
    delete:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/groups/model.json

/v1/participants:
  get:
    headers:
        x-access-token:
          displayName: Web token
    responses:
      200:
        body:
          application/json:
            schema: !include schema/participants/model.array.json

  /page/{page}/limit/{limit}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/participants/model.array.json

  /{participant_id}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/participants/model.json
    put:
      headers:
          x-access-token:
            displayName: Web token
      body:
        application/json:
          schema: !include schema/participants/model.post.json
      responses:
        200:
          body:
            application/json:
              schema: !include schema/participants/model.json
    delete:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/participants/model.json


/v1/rooms:
  get:
    headers:
        x-access-token:
          displayName: Web token
    responses:
      200:
        body:
          application/json:
            schema: !include schema/rooms/model.array.json

  /page/{page}/limit/{limit}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/rooms/model.array.json

  /{room_id}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/rooms/model.json
    put:
      headers:
          x-access-token:
            displayName: Web token
      body:
        application/json:
          schema: !include schema/rooms/model.post.json
      responses:
        200:
          body:
            application/json:
              schema: !include schema/rooms/model.json
    delete:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/rooms/model.json

/v1/states:
  get:
    headers:
        x-access-token:
          displayName: Web token
    responses:
      200:
        body:
          application/json:
            schema: !include schema/states/model.array.json

  /page/{page}/limit/{limit}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/states/model.array.json

  /{state_id}:
    get:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/states/model.json
    put:
      headers:
          x-access-token:
            displayName: Web token
      body:
        application/json:
          schema: !include schema/states/model.post.json
      responses:
        200:
          body:
            application/json:
              schema: !include schema/states/model.json
    delete:
      headers:
          x-access-token:
            displayName: Web token
      responses:
        200:
          body:
            application/json:
              schema: !include schema/states/model.json

# composite
/v1/areas/{area_id}/rooms/{room_id}/events/{event_id}/atts:
  post:
    headers:
        x-access-token:
          displayName: Web token
    body:
      application/json:
        schema: !include schema/atts/model.post.v1.json
    responses:
      200:
        body:
          application/json:
            schema: !include schema/atts/model.json
