# Server Metrics 2026-03-04 08:27:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 40637.5 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473942
telemt_connections_bad_total 8005
telemt_handshake_timeouts_total 6502
telemt_upstream_connect_attempt_total 25114
telemt_upstream_connect_success_total 25001
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 25001
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10860
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 261
telemt_me_reconnect_attempts_total 4895
telemt_me_reconnect_success_total 4860
telemt_me_reader_eof_total 4978
telemt_me_idle_close_by_peer_total 4978
telemt_me_route_drop_no_conn_total 160306
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 884
telemt_desync_full_logged_total 324
telemt_desync_suppressed_total 560
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 4978
telemt_me_writer_restored_same_endpoint_total 4839
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 400910
telemt_user_connections_current{user="hello"} 995
telemt_user_octets_from_client{user="hello"} 4671214276 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 119404333980 (111.20 GB)
telemt_user_unique_ips_current{user="hello"} 92
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 40634.0 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197890
telemt_connections_bad_total 1896
telemt_handshake_timeouts_total 24125
telemt_upstream_connect_attempt_total 83336
telemt_upstream_connect_success_total 82104
telemt_upstream_connect_fail_total 577
telemt_upstream_connect_attempts_per_request{bucket="1"} 82098
telemt_upstream_connect_attempts_per_request{bucket="2"} 583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 577
telemt_me_keepalive_timeout_total 1238
telemt_me_reconnect_attempts_total 48367
telemt_me_reconnect_success_total 48288
telemt_me_reader_eof_total 49505
telemt_me_idle_close_by_peer_total 49504
telemt_me_route_drop_no_conn_total 85485
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 173
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 432
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 277
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 49585
telemt_me_writer_restored_same_endpoint_total 48263
telemt_me_writer_removed_unexpected_minus_restored_total 1322
telemt_user_connections_total{user="hello"} 144361
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 1704146316 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 54464577956 (50.72 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 40632.8 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405437
telemt_connections_bad_total 116954
telemt_handshake_timeouts_total 11322
telemt_upstream_connect_attempt_total 60409
telemt_upstream_connect_success_total 60046
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 60045
telemt_upstream_connect_attempts_per_request{bucket="2"} 173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_timeout_total 803
telemt_me_reconnect_attempts_total 27757
telemt_me_reconnect_success_total 27686
telemt_me_reader_eof_total 29232
telemt_me_idle_close_by_peer_total 29229
telemt_me_route_drop_no_conn_total 133865
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 171
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 629
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 390
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_me_writer_removed_unexpected_total 29243
telemt_me_writer_restored_same_endpoint_total 27665
telemt_me_writer_removed_unexpected_minus_restored_total 1578
telemt_user_connections_total{user="hello"} 262155
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 2550157024 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 99455498556 (92.63 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 40631.8 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227709
telemt_connections_bad_total 18674
telemt_handshake_timeouts_total 8290
telemt_upstream_connect_attempt_total 30496
telemt_upstream_connect_success_total 30367
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 30367
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 6369
telemt_me_reconnect_success_total 6352
telemt_me_reader_eof_total 6472
telemt_me_idle_close_by_peer_total 6472
telemt_me_route_drop_no_conn_total 74463
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 11
telemt_pool_force_close_total 261
telemt_me_writer_removed_unexpected_total 6472
telemt_me_writer_restored_same_endpoint_total 6331
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 181541
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 2056156044 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 64150799820 (59.75 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 40630.5 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380257
telemt_connections_bad_total 6444
telemt_handshake_timeouts_total 131931
telemt_upstream_connect_attempt_total 60445
telemt_upstream_connect_success_total 60040
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 60040
telemt_upstream_connect_attempts_per_request{bucket="2"} 189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 806
telemt_me_reconnect_attempts_total 28818
telemt_me_reconnect_success_total 28795
telemt_me_reader_eof_total 30271
telemt_me_idle_close_by_peer_total 30270
telemt_me_route_drop_no_conn_total 108707
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 173
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 250
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 165
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 30284
telemt_me_writer_restored_same_endpoint_total 28770
telemt_me_writer_removed_unexpected_minus_restored_total 1514
telemt_user_connections_total{user="hello"} 232930
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 3104151516 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 58924047456 (54.88 GB)
telemt_user_unique_ips_current{user="hello"} 44
```