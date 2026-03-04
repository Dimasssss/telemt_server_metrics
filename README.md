# Server Metrics 2026-03-04 07:46:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 38177.6 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423294
telemt_connections_bad_total 7710
telemt_handshake_timeouts_total 6004
telemt_upstream_connect_attempt_total 23942
telemt_upstream_connect_success_total 23830
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 23830
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10296
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 253
telemt_me_reconnect_attempts_total 4772
telemt_me_reconnect_success_total 4741
telemt_me_reader_eof_total 4851
telemt_me_idle_close_by_peer_total 4851
telemt_me_route_drop_no_conn_total 138708
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 815
telemt_desync_full_logged_total 302
telemt_desync_suppressed_total 513
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 4851
telemt_me_writer_restored_same_endpoint_total 4720
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 353050
telemt_user_connections_current{user="hello"} 832
telemt_user_octets_from_client{user="hello"} 4176092724 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 105490816388 (98.25 GB)
telemt_user_unique_ips_current{user="hello"} 87
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 38174.1 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178259
telemt_connections_bad_total 1536
telemt_handshake_timeouts_total 23446
telemt_upstream_connect_attempt_total 77845
telemt_upstream_connect_success_total 76705
telemt_upstream_connect_fail_total 532
telemt_upstream_connect_attempts_per_request{bucket="1"} 76699
telemt_upstream_connect_attempts_per_request{bucket="2"} 538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 532
telemt_me_keepalive_timeout_total 1198
telemt_me_reconnect_attempts_total 45228
telemt_me_reconnect_success_total 45151
telemt_me_reader_eof_total 46257
telemt_me_idle_close_by_peer_total 46256
telemt_me_route_drop_no_conn_total 69160
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 165
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 359
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 46337
telemt_me_writer_restored_same_endpoint_total 45126
telemt_me_writer_removed_unexpected_minus_restored_total 1211
telemt_user_connections_total{user="hello"} 126226
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 1336913376 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 49556860760 (46.15 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 38172.9 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353940
telemt_connections_bad_total 107539
telemt_handshake_timeouts_total 10570
telemt_upstream_connect_attempt_total 57795
telemt_upstream_connect_success_total 57453
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 57452
telemt_upstream_connect_attempts_per_request{bucket="2"} 163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32893
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 762
telemt_me_reconnect_attempts_total 26392
telemt_me_reconnect_success_total 26324
telemt_me_reader_eof_total 27757
telemt_me_idle_close_by_peer_total 27754
telemt_me_route_drop_no_conn_total 107946
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 539
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 27768
telemt_me_writer_restored_same_endpoint_total 26303
telemt_me_writer_removed_unexpected_minus_restored_total 1465
telemt_user_connections_total{user="hello"} 226054
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 2106460820 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 81459566840 (75.87 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 38172.0 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202930
telemt_connections_bad_total 16456
telemt_handshake_timeouts_total 7701
telemt_upstream_connect_attempt_total 29169
telemt_upstream_connect_success_total 29048
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 29048
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 328
telemt_me_reconnect_attempts_total 6249
telemt_me_reconnect_success_total 6235
telemt_me_reader_eof_total 6354
telemt_me_idle_close_by_peer_total 6354
telemt_me_route_drop_no_conn_total 65789
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 11
telemt_pool_force_close_total 261
telemt_me_writer_removed_unexpected_total 6354
telemt_me_writer_restored_same_endpoint_total 6214
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 159933
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 1684965892 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 57421305100 (53.48 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 38170.6 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347240
telemt_connections_bad_total 6429
telemt_handshake_timeouts_total 130256
telemt_upstream_connect_attempt_total 54638
telemt_upstream_connect_success_total 54258
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 54258
telemt_upstream_connect_attempts_per_request{bucket="2"} 177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21679
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 747
telemt_me_reconnect_attempts_total 25370
telemt_me_reconnect_success_total 25352
telemt_me_reader_eof_total 26682
telemt_me_idle_close_by_peer_total 26681
telemt_me_route_drop_no_conn_total 96440
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 162
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 231
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 26696
telemt_me_writer_restored_same_endpoint_total 25327
telemt_me_writer_removed_unexpected_minus_restored_total 1369
telemt_user_connections_total{user="hello"} 203821
telemt_user_connections_current{user="hello"} 396
telemt_user_octets_from_client{user="hello"} 2625289092 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 49025276868 (45.66 GB)
telemt_user_unique_ips_current{user="hello"} 39
```