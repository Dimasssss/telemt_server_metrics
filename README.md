# Server Metrics 2026-03-13 20:41:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 139401.4 (38h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4424091
telemt_connections_bad_total 37959
telemt_handshake_timeouts_total 106113
telemt_upstream_connect_attempt_total 29119
telemt_upstream_connect_success_total 28920
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 29119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 6556
telemt_me_reconnect_attempts_total 29761
telemt_me_reconnect_success_total 19643
telemt_me_reader_eof_total 21079
telemt_me_idle_close_by_peer_total 21078
telemt_me_route_drop_no_conn_total 1666691
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4050464
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16121
telemt_desync_full_logged_total 4298
telemt_desync_suppressed_total 11823
telemt_desync_frames_bucket_total{bucket="1_2"} 4023
telemt_desync_frames_bucket_total{bucket="3_10"} 6145
telemt_desync_frames_bucket_total{bucket="gt_10"} 5953
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 20241
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19630
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 598
telemt_user_connections_total{user="hello"} 4052600
telemt_user_connections_current{user="hello"} 1304
telemt_user_octets_from_client{user="hello"} 59825506132 (55.72 GB)
telemt_user_octets_to_client{user="hello"} 1279613750825 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 39065.3 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 550379
telemt_connections_bad_total 41394
telemt_handshake_timeouts_total 12163
telemt_upstream_connect_attempt_total 11209
telemt_upstream_connect_success_total 10991
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 11209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 1882
telemt_me_reconnect_attempts_total 10409
telemt_me_reconnect_success_total 6988
telemt_me_reader_eof_total 7385
telemt_me_idle_close_by_peer_total 7384
telemt_me_route_drop_no_conn_total 203557
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477506
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1618
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 1184
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 705
telemt_desync_frames_bucket_total{bucket="gt_10"} 569
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 7194
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6980
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 479435
telemt_user_connections_current{user="hello"} 427
telemt_user_octets_from_client{user="hello"} 5152142993 (4.80 GB)
telemt_user_octets_to_client{user="hello"} 151895627176 (141.46 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 169022.1 (46h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3220102
telemt_connections_bad_total 29854
telemt_handshake_timeouts_total 214648
telemt_upstream_connect_attempt_total 37604
telemt_upstream_connect_success_total 37584
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 37604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 10222
telemt_me_reconnect_attempts_total 32487
telemt_me_reconnect_success_total 28856
telemt_me_reader_eof_total 30582
telemt_me_idle_close_by_peer_total 30581
telemt_me_route_drop_no_conn_total 1103570
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2669853
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8830
telemt_desync_full_logged_total 2958
telemt_desync_suppressed_total 5872
telemt_desync_frames_bucket_total{bucket="1_2"} 1462
telemt_desync_frames_bucket_total{bucket="3_10"} 3224
telemt_desync_frames_bucket_total{bucket="gt_10"} 4144
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 29238
telemt_me_refill_failed_total 108
telemt_me_writer_restored_same_endpoint_total 28815
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 2669134
telemt_user_connections_current{user="hello"} 790
telemt_user_octets_from_client{user="hello"} 43919156236 (40.90 GB)
telemt_user_octets_to_client{user="hello"} 939106994669 (874.61 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 169022.5 (46h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2089921
telemt_connections_bad_total 22773
telemt_handshake_timeouts_total 199743
telemt_upstream_connect_attempt_total 52678
telemt_upstream_connect_success_total 50239
telemt_upstream_connect_fail_total 2302
telemt_upstream_connect_attempts_per_request{bucket="1"} 52404
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2301
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20219
telemt_me_reconnect_attempts_total 43819
telemt_me_reconnect_success_total 34808
telemt_me_reader_eof_total 37367
telemt_me_idle_close_by_peer_total 37360
telemt_me_route_drop_no_conn_total 737963
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1720819
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3690
telemt_desync_full_logged_total 1180
telemt_desync_suppressed_total 2510
telemt_desync_frames_bucket_total{bucket="1_2"} 976
telemt_desync_frames_bucket_total{bucket="3_10"} 1531
telemt_desync_frames_bucket_total{bucket="gt_10"} 1183
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 35387
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34784
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 1726690
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 26804447023 (24.96 GB)
telemt_user_octets_to_client{user="hello"} 646078478954 (601.71 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 38457.9 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588481
telemt_connections_bad_total 5785
telemt_handshake_timeouts_total 5562
telemt_upstream_connect_attempt_total 8495
telemt_upstream_connect_success_total 8224
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 8495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4269
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 969
telemt_me_reconnect_attempts_total 29535
telemt_me_reconnect_success_total 6291
telemt_me_reader_eof_total 7138
telemt_me_idle_close_by_peer_total 7137
telemt_me_route_drop_no_conn_total 222912
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 552351
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1482
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 7074
telemt_me_refill_failed_total 724
telemt_me_writer_restored_same_endpoint_total 6287
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 783
telemt_user_connections_total{user="hello"} 552287
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 8260665668 (7.69 GB)
telemt_user_octets_to_client{user="hello"} 175826161860 (163.75 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 51
```