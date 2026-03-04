# Server Metrics 2026-03-04 08:12:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 39715.9 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 455562
telemt_connections_bad_total 7973
telemt_handshake_timeouts_total 6294
telemt_upstream_connect_attempt_total 24562
telemt_upstream_connect_success_total 24449
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 24449
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 258
telemt_me_reconnect_attempts_total 4794
telemt_me_reconnect_success_total 4760
telemt_me_reader_eof_total 4872
telemt_me_idle_close_by_peer_total 4872
telemt_me_route_drop_no_conn_total 153627
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 871
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 554
telemt_desync_frames_bucket_total{bucket="1_2"} 251
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 297
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 4872
telemt_me_writer_restored_same_endpoint_total 4739
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 383167
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 4452449028 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 114078283784 (106.24 GB)
telemt_user_unique_ips_current{user="hello"} 81
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 39712.4 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190449
telemt_connections_bad_total 1860
telemt_handshake_timeouts_total 23716
telemt_upstream_connect_attempt_total 81062
telemt_upstream_connect_success_total 79877
telemt_upstream_connect_fail_total 554
telemt_upstream_connect_attempts_per_request{bucket="1"} 79871
telemt_upstream_connect_attempts_per_request{bucket="2"} 560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 554
telemt_me_keepalive_timeout_total 1217
telemt_me_reconnect_attempts_total 47032
telemt_me_reconnect_success_total 46955
telemt_me_reader_eof_total 48115
telemt_me_idle_close_by_peer_total 48114
telemt_me_route_drop_no_conn_total 80007
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 402
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 48195
telemt_me_writer_restored_same_endpoint_total 46930
telemt_me_writer_removed_unexpected_minus_restored_total 1265
telemt_user_connections_total{user="hello"} 137520
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 1659153476 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 52953683812 (49.32 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 39711.3 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387140
telemt_connections_bad_total 112149
telemt_handshake_timeouts_total 11074
telemt_upstream_connect_attempt_total 59961
telemt_upstream_connect_success_total 59615
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 59614
telemt_upstream_connect_attempts_per_request{bucket="2"} 165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 799
telemt_me_reconnect_attempts_total 27711
telemt_me_reconnect_success_total 27640
telemt_me_reader_eof_total 29185
telemt_me_idle_close_by_peer_total 29182
telemt_me_route_drop_no_conn_total 122603
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 610
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 382
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_me_writer_removed_unexpected_total 29196
telemt_me_writer_restored_same_endpoint_total 27619
telemt_me_writer_removed_unexpected_minus_restored_total 1577
telemt_user_connections_total{user="hello"} 249082
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 2419316168 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 93091975260 (86.70 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 39710.2 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217913
telemt_connections_bad_total 17838
telemt_handshake_timeouts_total 7912
telemt_upstream_connect_attempt_total 29797
telemt_upstream_connect_success_total 29670
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 29670
telemt_upstream_connect_attempts_per_request{bucket="2"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 336
telemt_me_reconnect_attempts_total 6268
telemt_me_reconnect_success_total 6252
telemt_me_reader_eof_total 6371
telemt_me_idle_close_by_peer_total 6371
telemt_me_route_drop_no_conn_total 71205
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 11
telemt_pool_force_close_total 261
telemt_me_writer_removed_unexpected_total 6371
telemt_me_writer_restored_same_endpoint_total 6231
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 173098
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 1780080868 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 61886813020 (57.64 GB)
telemt_user_unique_ips_current{user="hello"} 31
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 39708.9 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367362
telemt_connections_bad_total 6442
telemt_handshake_timeouts_total 131573
telemt_upstream_connect_attempt_total 58107
telemt_upstream_connect_success_total 57710
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 57710
telemt_upstream_connect_attempts_per_request{bucket="2"} 185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 783
telemt_me_reconnect_attempts_total 27359
telemt_me_reconnect_success_total 27338
telemt_me_reader_eof_total 28761
telemt_me_idle_close_by_peer_total 28760
telemt_me_route_drop_no_conn_total 104553
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 247
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 28775
telemt_me_writer_restored_same_endpoint_total 27313
telemt_me_writer_removed_unexpected_minus_restored_total 1462
telemt_user_connections_total{user="hello"} 221680
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 2931833584 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 56185136580 (52.33 GB)
telemt_user_unique_ips_current{user="hello"} 34
```