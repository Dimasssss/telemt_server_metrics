# Server Metrics 2026-03-14 08:32:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 182040.5 (50h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5156418
telemt_connections_bad_total 43322
telemt_handshake_timeouts_total 116597
telemt_upstream_connect_attempt_total 38332
telemt_upstream_connect_success_total 38082
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 38332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 7419
telemt_me_reconnect_attempts_total 37896
telemt_me_reconnect_success_total 26685
telemt_me_reader_eof_total 28641
telemt_me_idle_close_by_peer_total 28640
telemt_me_route_drop_no_conn_total 1951750
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4728901
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18016
telemt_desync_full_logged_total 4908
telemt_desync_suppressed_total 13108
telemt_desync_frames_bucket_total{bucket="1_2"} 4489
telemt_desync_frames_bucket_total{bucket="3_10"} 6830
telemt_desync_frames_bucket_total{bucket="gt_10"} 6697
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 27422
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26672
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 737
telemt_user_connections_total{user="hello"} 4730357
telemt_user_connections_current{user="hello"} 1725
telemt_user_octets_from_client{user="hello"} 72549714544 (67.57 GB)
telemt_user_octets_to_client{user="hello"} 1512961578553 (1.38 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 81704.4 (22h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 898471
telemt_connections_bad_total 53926
telemt_handshake_timeouts_total 17109
telemt_upstream_connect_attempt_total 21951
telemt_upstream_connect_success_total 21671
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 21951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_keepalive_timeout_total 2178
telemt_me_reconnect_attempts_total 20080
telemt_me_reconnect_success_total 15586
telemt_me_reader_eof_total 16573
telemt_me_idle_close_by_peer_total 16572
telemt_me_route_drop_no_conn_total 298460
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 726080
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2172
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 1492
telemt_desync_frames_bucket_total{bucket="1_2"} 493
telemt_desync_frames_bucket_total{bucket="3_10"} 933
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15952
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 15578
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 727979
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 7711787365 (7.18 GB)
telemt_user_octets_to_client{user="hello"} 252803254160 (235.44 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 211661.1 (58h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3682697
telemt_connections_bad_total 43225
telemt_handshake_timeouts_total 242009
telemt_upstream_connect_attempt_total 47775
telemt_upstream_connect_success_total 47754
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22271
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10776
telemt_me_reconnect_attempts_total 41881
telemt_me_reconnect_success_total 36895
telemt_me_reader_eof_total 39181
telemt_me_idle_close_by_peer_total 39180
telemt_me_route_drop_no_conn_total 1263201
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3074406
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10049
telemt_desync_full_logged_total 3389
telemt_desync_suppressed_total 6660
telemt_desync_frames_bucket_total{bucket="1_2"} 1772
telemt_desync_frames_bucket_total{bucket="3_10"} 3636
telemt_desync_frames_bucket_total{bucket="gt_10"} 4641
telemt_pool_swap_total 200
telemt_me_writer_removed_unexpected_total 37407
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36854
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 3073541
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 52232272016 (48.65 GB)
telemt_user_octets_to_client{user="hello"} 1099069621057 (1023.59 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 211663.7 (58h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2444769
telemt_connections_bad_total 23349
telemt_handshake_timeouts_total 298201
telemt_upstream_connect_attempt_total 65791
telemt_upstream_connect_success_total 63294
telemt_upstream_connect_fail_total 2360
telemt_upstream_connect_attempts_per_request{bucket="1"} 65517
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25352
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2359
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20576
telemt_me_reconnect_attempts_total 54810
telemt_me_reconnect_success_total 45726
telemt_me_reader_eof_total 48978
telemt_me_idle_close_by_peer_total 48971
telemt_me_route_drop_no_conn_total 819469
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1922578
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3952
telemt_desync_full_logged_total 1290
telemt_desync_suppressed_total 2662
telemt_desync_frames_bucket_total{bucket="1_2"} 1095
telemt_desync_frames_bucket_total{bucket="3_10"} 1623
telemt_desync_frames_bucket_total{bucket="gt_10"} 1234
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46402
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45702
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 676
telemt_user_connections_total{user="hello"} 1928709
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 28871880531 (26.89 GB)
telemt_user_octets_to_client{user="hello"} 701571269962 (653.39 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 81097.2 (22h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 881401
telemt_connections_bad_total 10676
telemt_handshake_timeouts_total 10452
telemt_upstream_connect_attempt_total 20477
telemt_upstream_connect_success_total 19928
telemt_upstream_connect_fail_total 549
telemt_upstream_connect_attempts_per_request{bucket="1"} 20477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 549
telemt_me_keepalive_timeout_total 1627
telemt_me_reconnect_attempts_total 66407
telemt_me_reconnect_success_total 15875
telemt_me_reader_eof_total 17837
telemt_me_idle_close_by_peer_total 17836
telemt_me_route_drop_no_conn_total 336763
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 821184
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 1444
telemt_desync_frames_bucket_total{bucket="1_2"} 676
telemt_desync_frames_bucket_total{bucket="3_10"} 798
telemt_desync_frames_bucket_total{bucket="gt_10"} 632
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 17592
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 15870
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1717
telemt_user_connections_total{user="hello"} 821039
telemt_user_connections_current{user="hello"} 728
telemt_user_octets_from_client{user="hello"} 14958865424 (13.93 GB)
telemt_user_octets_to_client{user="hello"} 277623722380 (258.56 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 110
```