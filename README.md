# Server Metrics 2026-03-12 15:15:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 33419.6 (9h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1201341
telemt_connections_bad_total 20230
telemt_handshake_timeouts_total 12160
telemt_upstream_connect_attempt_total 6652
telemt_upstream_connect_success_total 6616
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 6652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 8796
telemt_me_reconnect_success_total 4892
telemt_me_reader_eof_total 5211
telemt_me_idle_close_by_peer_total 5210
telemt_me_route_drop_no_conn_total 426567
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1130365
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6026
telemt_desync_full_logged_total 1507
telemt_desync_suppressed_total 4519
telemt_desync_frames_bucket_total{bucket="1_2"} 1541
telemt_desync_frames_bucket_total{bucket="3_10"} 2166
telemt_desync_frames_bucket_total{bucket="gt_10"} 2319
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5071
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4879
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 1130090
telemt_user_connections_current{user="hello"} 1565
telemt_user_octets_from_client{user="hello"} 17759946432 (16.54 GB)
telemt_user_octets_to_client{user="hello"} 330075733124 (307.41 GB)
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 269
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 63040.2 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 544969
telemt_connections_bad_total 6617
telemt_handshake_timeouts_total 27094
telemt_upstream_connect_attempt_total 15134
telemt_upstream_connect_success_total 15127
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1178
telemt_me_reconnect_attempts_total 11868
telemt_me_reconnect_success_total 11802
telemt_me_reader_eof_total 12541
telemt_me_idle_close_by_peer_total 12541
telemt_me_route_drop_no_conn_total 159304
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 485692
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1863
telemt_desync_full_logged_total 587
telemt_desync_suppressed_total 1276
telemt_desync_frames_bucket_total{bucket="1_2"} 813
telemt_desync_frames_bucket_total{bucket="3_10"} 599
telemt_desync_frames_bucket_total{bucket="gt_10"} 451
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 11913
telemt_me_writer_restored_same_endpoint_total 11793
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 486190
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 7441167547 (6.93 GB)
telemt_user_octets_to_client{user="hello"} 171106405414 (159.36 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 63040.1 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1164305
telemt_connections_bad_total 6159
telemt_handshake_timeouts_total 81417
telemt_upstream_connect_attempt_total 15102
telemt_upstream_connect_success_total 15097
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 982
telemt_me_reconnect_attempts_total 12818
telemt_me_reconnect_success_total 11597
telemt_me_reader_eof_total 12233
telemt_me_idle_close_by_peer_total 12233
telemt_me_route_drop_no_conn_total 311350
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 852841
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3545
telemt_desync_full_logged_total 1093
telemt_desync_suppressed_total 2452
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 1285
telemt_desync_frames_bucket_total{bucket="gt_10"} 1721
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11681
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11556
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 853028
telemt_user_connections_current{user="hello"} 1086
telemt_user_octets_from_client{user="hello"} 11258845316 (10.49 GB)
telemt_user_octets_to_client{user="hello"} 267276887113 (248.92 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 63040.5 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688473
telemt_connections_bad_total 7700
telemt_handshake_timeouts_total 57709
telemt_upstream_connect_attempt_total 16718
telemt_upstream_connect_success_total 16649
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 16718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1366
telemt_me_reconnect_attempts_total 17373
telemt_me_reconnect_success_total 13512
telemt_me_reader_eof_total 14368
telemt_me_idle_close_by_peer_total 14368
telemt_me_route_drop_no_conn_total 232630
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 589359
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1172
telemt_desync_full_logged_total 404
telemt_desync_suppressed_total 768
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 468
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13734
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 13491
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 588858
telemt_user_connections_current{user="hello"} 712
telemt_user_octets_from_client{user="hello"} 7092189980 (6.61 GB)
telemt_user_octets_to_client{user="hello"} 233861209296 (217.80 GB)
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 63040.6 (17h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 774449
telemt_connections_bad_total 6990
telemt_handshake_timeouts_total 6170
telemt_upstream_connect_attempt_total 19809
telemt_upstream_connect_success_total 19565
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 19809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9525
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 1111
telemt_me_reconnect_attempts_total 23658
telemt_me_reconnect_success_total 16425
telemt_me_reader_eof_total 17191
telemt_me_idle_close_by_peer_total 17191
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 269512
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 715470
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2860
telemt_desync_full_logged_total 965
telemt_desync_suppressed_total 1895
telemt_desync_frames_bucket_total{bucket="1_2"} 809
telemt_desync_frames_bucket_total{bucket="3_10"} 979
telemt_desync_frames_bucket_total{bucket="gt_10"} 1072
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 16819
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 16391
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 715369
telemt_user_connections_current{user="hello"} 951
telemt_user_octets_from_client{user="hello"} 8521158316 (7.94 GB)
telemt_user_octets_to_client{user="hello"} 199167319436 (185.49 GB)
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 165
```