# Server Metrics 2026-03-14 08:37:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 182347.2 (50h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5166197
telemt_connections_bad_total 43570
telemt_handshake_timeouts_total 116653
telemt_upstream_connect_attempt_total 38364
telemt_upstream_connect_success_total 38114
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 38364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 7419
telemt_me_reconnect_attempts_total 37928
telemt_me_reconnect_success_total 26717
telemt_me_reader_eof_total 28674
telemt_me_idle_close_by_peer_total 28673
telemt_me_route_drop_no_conn_total 1955885
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4738220
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18088
telemt_desync_full_logged_total 4925
telemt_desync_suppressed_total 13163
telemt_desync_frames_bucket_total{bucket="1_2"} 4497
telemt_desync_frames_bucket_total{bucket="3_10"} 6865
telemt_desync_frames_bucket_total{bucket="gt_10"} 6726
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 27455
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26704
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 4739671
telemt_user_connections_current{user="hello"} 1585
telemt_user_octets_from_client{user="hello"} 72664080580 (67.67 GB)
telemt_user_octets_to_client{user="hello"} 1516242096365 (1.38 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 82011.2 (22h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 902494
telemt_connections_bad_total 54146
telemt_handshake_timeouts_total 17190
telemt_upstream_connect_attempt_total 22035
telemt_upstream_connect_success_total 21754
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 22035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 2179
telemt_me_reconnect_attempts_total 20123
telemt_me_reconnect_success_total 15629
telemt_me_reader_eof_total 16616
telemt_me_idle_close_by_peer_total 16615
telemt_me_route_drop_no_conn_total 300186
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 729718
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2173
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1492
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 933
telemt_desync_frames_bucket_total{bucket="gt_10"} 746
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15995
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 15621
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 731617
telemt_user_connections_current{user="hello"} 553
telemt_user_octets_from_client{user="hello"} 7738036185 (7.21 GB)
telemt_user_octets_to_client{user="hello"} 254123836364 (236.67 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 211967.9 (58h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3689880
telemt_connections_bad_total 43279
telemt_handshake_timeouts_total 242490
telemt_upstream_connect_attempt_total 47831
telemt_upstream_connect_success_total 47810
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22300
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10793
telemt_me_reconnect_attempts_total 41937
telemt_me_reconnect_success_total 36951
telemt_me_reader_eof_total 39241
telemt_me_idle_close_by_peer_total 39240
telemt_me_route_drop_no_conn_total 1266110
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3080843
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10077
telemt_desync_full_logged_total 3403
telemt_desync_suppressed_total 6674
telemt_desync_frames_bucket_total{bucket="1_2"} 1781
telemt_desync_frames_bucket_total{bucket="3_10"} 3649
telemt_desync_frames_bucket_total{bucket="gt_10"} 4647
telemt_pool_swap_total 200
telemt_me_writer_removed_unexpected_total 37463
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 36910
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 3079983
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 52311948240 (48.72 GB)
telemt_user_octets_to_client{user="hello"} 1100948371505 (1.00 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 211970.4 (58h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2448626
telemt_connections_bad_total 23350
telemt_handshake_timeouts_total 298896
telemt_upstream_connect_attempt_total 65919
telemt_upstream_connect_success_total 63422
telemt_upstream_connect_fail_total 2360
telemt_upstream_connect_attempts_per_request{bucket="1"} 65645
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2359
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20578
telemt_me_reconnect_attempts_total 54938
telemt_me_reconnect_success_total 45853
telemt_me_reader_eof_total 49105
telemt_me_idle_close_by_peer_total 49098
telemt_me_route_drop_no_conn_total 820721
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1925561
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3968
telemt_desync_full_logged_total 1293
telemt_desync_suppressed_total 2675
telemt_desync_frames_bucket_total{bucket="1_2"} 1097
telemt_desync_frames_bucket_total{bucket="3_10"} 1630
telemt_desync_frames_bucket_total{bucket="gt_10"} 1241
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46529
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 45829
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 676
telemt_user_connections_total{user="hello"} 1931692
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 28920089799 (26.93 GB)
telemt_user_octets_to_client{user="hello"} 702259780790 (654.03 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 81403.9 (22h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 886406
telemt_connections_bad_total 10911
telemt_handshake_timeouts_total 10517
telemt_upstream_connect_attempt_total 20547
telemt_upstream_connect_success_total 19998
telemt_upstream_connect_fail_total 549
telemt_upstream_connect_attempts_per_request{bucket="1"} 20547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 549
telemt_me_keepalive_timeout_total 1630
telemt_me_reconnect_attempts_total 66471
telemt_me_reconnect_success_total 15938
telemt_me_reader_eof_total 17912
telemt_me_idle_close_by_peer_total 17911
telemt_me_route_drop_no_conn_total 338521
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 825686
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2122
telemt_desync_full_logged_total 667
telemt_desync_suppressed_total 1455
telemt_desync_frames_bucket_total{bucket="1_2"} 683
telemt_desync_frames_bucket_total{bucket="3_10"} 804
telemt_desync_frames_bucket_total{bucket="gt_10"} 635
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 17658
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 15933
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1720
telemt_user_connections_total{user="hello"} 825541
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 15037074776 (14.00 GB)
telemt_user_octets_to_client{user="hello"} 280306702684 (261.06 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 97
```