# Server Metrics 2026-03-04 05:54:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 31403.7 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245533
telemt_connections_bad_total 2423
telemt_handshake_timeouts_total 4857
telemt_upstream_connect_attempt_total 21191
telemt_upstream_connect_success_total 21094
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 21094
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9076
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 4607
telemt_me_reconnect_success_total 4585
telemt_me_reader_eof_total 4690
telemt_me_idle_close_by_peer_total 4690
telemt_me_route_drop_no_conn_total 87197
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 648
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 227
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_me_writer_removed_unexpected_total 4690
telemt_me_writer_restored_same_endpoint_total 4565
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 232028
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 2436405964 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 75110615652 (69.95 GB)
telemt_user_unique_ips_current{user="hello"} 82
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 31400.2 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120056
telemt_connections_bad_total 362
telemt_handshake_timeouts_total 21975
telemt_upstream_connect_attempt_total 70495
telemt_upstream_connect_success_total 69647
telemt_upstream_connect_fail_total 407
telemt_upstream_connect_attempts_per_request{bucket="1"} 69641
telemt_upstream_connect_attempts_per_request{bucket="2"} 413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 407
telemt_me_keepalive_timeout_total 1023
telemt_me_reconnect_attempts_total 42275
telemt_me_reconnect_success_total 42246
telemt_me_reader_eof_total 43310
telemt_me_idle_close_by_peer_total 43309
telemt_me_route_drop_no_conn_total 37197
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 255
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 159
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 43371
telemt_me_writer_restored_same_endpoint_total 42225
telemt_me_writer_removed_unexpected_minus_restored_total 1146
telemt_user_connections_total{user="hello"} 84298
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 754897212 (719.93 MB)
telemt_user_octets_to_client{user="hello"} 35435504500 (33.00 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 31399.1 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255301
telemt_connections_bad_total 89950
telemt_handshake_timeouts_total 5325
telemt_upstream_connect_attempt_total 42056
telemt_upstream_connect_success_total 41789
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 41789
telemt_upstream_connect_attempts_per_request{bucket="2"} 125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17364
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 17138
telemt_me_reconnect_success_total 17092
telemt_me_reader_eof_total 18015
telemt_me_idle_close_by_peer_total 18012
telemt_me_route_drop_no_conn_total 54584
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 133
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 372
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 236
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 18023
telemt_me_writer_restored_same_endpoint_total 17071
telemt_me_writer_removed_unexpected_minus_restored_total 952
telemt_user_connections_total{user="hello"} 152449
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 1106207324 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 39918901684 (37.18 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 31398.1 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131129
telemt_connections_bad_total 9775
telemt_handshake_timeouts_total 2502
telemt_upstream_connect_attempt_total 23886
telemt_upstream_connect_success_total 23797
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 23797
telemt_upstream_connect_attempts_per_request{bucket="2"} 44
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 250
telemt_me_reconnect_attempts_total 4859
telemt_me_reconnect_success_total 4853
telemt_me_reader_eof_total 4930
telemt_me_idle_close_by_peer_total 4930
telemt_me_route_drop_no_conn_total 39585
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 131
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 141
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 4930
telemt_me_writer_restored_same_endpoint_total 4832
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 112428
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 981230712 (935.77 MB)
telemt_user_octets_to_client{user="hello"} 42006427460 (39.12 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 31396.7 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 271370
telemt_connections_bad_total 5437
telemt_handshake_timeouts_total 123053
telemt_upstream_connect_attempt_total 45053
telemt_upstream_connect_success_total 44738
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 44738
telemt_upstream_connect_attempts_per_request{bucket="2"} 148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 616
telemt_me_reconnect_attempts_total 21435
telemt_me_reconnect_success_total 21424
telemt_me_reader_eof_total 22607
telemt_me_idle_close_by_peer_total 22606
telemt_me_route_drop_no_conn_total 60453
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 199
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22620
telemt_me_writer_restored_same_endpoint_total 21399
telemt_me_writer_removed_unexpected_minus_restored_total 1221
telemt_user_connections_total{user="hello"} 138193
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 1970864664 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 31986279712 (29.79 GB)
telemt_user_unique_ips_current{user="hello"} 31
```