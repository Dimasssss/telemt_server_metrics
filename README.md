# Server Metrics 2026-03-14 06:55:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 176209.9 (48h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4963106
telemt_connections_bad_total 40205
telemt_handshake_timeouts_total 113100
telemt_upstream_connect_attempt_total 36950
telemt_upstream_connect_success_total 36709
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 36950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_timeout_total 7329
telemt_me_reconnect_attempts_total 35773
telemt_me_reconnect_success_total 25622
telemt_me_reader_eof_total 27496
telemt_me_idle_close_by_peer_total 27495
telemt_me_route_drop_no_conn_total 1879191
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4554078
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17408
telemt_desync_full_logged_total 4720
telemt_desync_suppressed_total 12688
telemt_desync_frames_bucket_total{bucket="1_2"} 4344
telemt_desync_frames_bucket_total{bucket="3_10"} 6629
telemt_desync_frames_bucket_total{bucket="gt_10"} 6435
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 26307
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25609
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 685
telemt_user_connections_total{user="hello"} 4555565
telemt_user_connections_current{user="hello"} 1427
telemt_user_octets_from_client{user="hello"} 66692993240 (62.11 GB)
telemt_user_octets_to_client{user="hello"} 1434375945237 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 75873.9 (21h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 826266
telemt_connections_bad_total 53811
telemt_handshake_timeouts_total 15115
telemt_upstream_connect_attempt_total 20575
telemt_upstream_connect_success_total 20304
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 20575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 2144
telemt_me_reconnect_attempts_total 17950
telemt_me_reconnect_success_total 14486
telemt_me_reader_eof_total 15399
telemt_me_idle_close_by_peer_total 15398
telemt_me_route_drop_no_conn_total 271009
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 657953
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1899
telemt_desync_full_logged_total 579
telemt_desync_suppressed_total 1320
telemt_desync_frames_bucket_total{bucket="1_2"} 390
telemt_desync_frames_bucket_total{bucket="3_10"} 855
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 14800
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14478
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 659869
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 6942236613 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 223256983504 (207.92 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 205830.6 (57h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3563070
telemt_connections_bad_total 41688
telemt_handshake_timeouts_total 234166
telemt_upstream_connect_attempt_total 46490
telemt_upstream_connect_success_total 46469
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21722
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10679
telemt_me_reconnect_attempts_total 40903
telemt_me_reconnect_success_total 35928
telemt_me_reader_eof_total 38164
telemt_me_idle_close_by_peer_total 38163
telemt_me_route_drop_no_conn_total 1217644
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2970540
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9802
telemt_desync_full_logged_total 3290
telemt_desync_suppressed_total 6512
telemt_desync_frames_bucket_total{bucket="1_2"} 1704
telemt_desync_frames_bucket_total{bucket="3_10"} 3544
telemt_desync_frames_bucket_total{bucket="gt_10"} 4554
telemt_pool_swap_total 195
telemt_me_writer_removed_unexpected_total 36426
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35887
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 2969691
telemt_user_connections_current{user="hello"} 745
telemt_user_octets_from_client{user="hello"} 49644337184 (46.23 GB)
telemt_user_octets_to_client{user="hello"} 1060141444025 (987.33 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 205833.2 (57h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2374902
telemt_connections_bad_total 23300
telemt_handshake_timeouts_total 281738
telemt_upstream_connect_attempt_total 64087
telemt_upstream_connect_success_total 61598
telemt_upstream_connect_fail_total 2352
telemt_upstream_connect_attempts_per_request{bucket="1"} 63813
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24670
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2351
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20516
telemt_me_reconnect_attempts_total 53393
telemt_me_reconnect_success_total 44347
telemt_me_reader_eof_total 47544
telemt_me_idle_close_by_peer_total 47537
telemt_me_route_drop_no_conn_total 799928
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1872837
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3910
telemt_desync_full_logged_total 1268
telemt_desync_suppressed_total 2642
telemt_desync_frames_bucket_total{bucket="1_2"} 1067
telemt_desync_frames_bucket_total{bucket="3_10"} 1617
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 183
telemt_me_writer_removed_unexpected_total 45013
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 44323
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 666
telemt_user_connections_total{user="hello"} 1878901
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 28310252603 (26.37 GB)
telemt_user_octets_to_client{user="hello"} 690687704438 (643.25 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 75266.4 (20h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 799195
telemt_connections_bad_total 8105
telemt_handshake_timeouts_total 9393
telemt_upstream_connect_attempt_total 19155
telemt_upstream_connect_success_total 18639
telemt_upstream_connect_fail_total 516
telemt_upstream_connect_attempts_per_request{bucket="1"} 19155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 516
telemt_me_keepalive_timeout_total 1583
telemt_me_reconnect_attempts_total 60196
telemt_me_reconnect_success_total 14890
telemt_me_reader_eof_total 16671
telemt_me_idle_close_by_peer_total 16670
telemt_me_route_drop_no_conn_total 307773
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 746695
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1821
telemt_desync_full_logged_total 582
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 701
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 16433
telemt_me_refill_failed_total 1411
telemt_me_writer_restored_same_endpoint_total 14885
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1543
telemt_user_connections_total{user="hello"} 746556
telemt_user_connections_current{user="hello"} 595
telemt_user_octets_from_client{user="hello"} 13225294256 (12.32 GB)
telemt_user_octets_to_client{user="hello"} 251646453260 (234.36 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 86
```