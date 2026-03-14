# Server Metrics 2026-03-14 11:57:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 194324.1 (53h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5623010
telemt_connections_bad_total 58953
telemt_handshake_timeouts_total 123689
telemt_upstream_connect_attempt_total 40661
telemt_upstream_connect_success_total 40401
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 40661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 7841
telemt_me_reconnect_attempts_total 44786
telemt_me_reconnect_success_total 28414
telemt_me_reader_eof_total 30590
telemt_me_idle_close_by_peer_total 30589
telemt_me_route_drop_no_conn_total 2127953
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5158302
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19893
telemt_desync_full_logged_total 5433
telemt_desync_suppressed_total 14460
telemt_desync_frames_bucket_total{bucket="1_2"} 4822
telemt_desync_frames_bucket_total{bucket="3_10"} 7584
telemt_desync_frames_bucket_total{bucket="gt_10"} 7487
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29339
telemt_me_refill_failed_total 506
telemt_me_writer_restored_same_endpoint_total 28401
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 925
telemt_user_connections_total{user="hello"} 5159789
telemt_user_connections_current{user="hello"} 1862
telemt_user_octets_from_client{user="hello"} 80077682616 (74.58 GB)
telemt_user_octets_to_client{user="hello"} 1642223644061 (1.49 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 486
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 93988.0 (26h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1078323
telemt_connections_bad_total 58919
telemt_handshake_timeouts_total 24758
telemt_upstream_connect_attempt_total 24391
telemt_upstream_connect_success_total 24090
telemt_upstream_connect_fail_total 301
telemt_upstream_connect_attempts_per_request{bucket="1"} 24391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 301
telemt_me_keepalive_timeout_total 2401
telemt_me_reconnect_attempts_total 33750
telemt_me_reconnect_success_total 17373
telemt_me_reader_eof_total 18775
telemt_me_idle_close_by_peer_total 18774
telemt_me_route_drop_no_conn_total 363719
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 887275
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2461
telemt_desync_full_logged_total 771
telemt_desync_suppressed_total 1690
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 1024
telemt_desync_frames_bucket_total{bucket="gt_10"} 805
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18130
telemt_me_refill_failed_total 505
telemt_me_writer_restored_same_endpoint_total 17365
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 757
telemt_user_connections_total{user="hello"} 889187
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 9744703417 (9.08 GB)
telemt_user_octets_to_client{user="hello"} 313412444256 (291.89 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 223944.7 (62h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3987866
telemt_connections_bad_total 46189
telemt_handshake_timeouts_total 270888
telemt_upstream_connect_attempt_total 50469
telemt_upstream_connect_success_total 50448
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 50469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11254
telemt_me_reconnect_attempts_total 44986
telemt_me_reconnect_success_total 38985
telemt_me_reader_eof_total 41409
telemt_me_idle_close_by_peer_total 41407
telemt_me_route_drop_no_conn_total 1370037
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3335410
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10718
telemt_desync_full_logged_total 3623
telemt_desync_suppressed_total 7095
telemt_desync_frames_bucket_total{bucket="1_2"} 1953
telemt_desync_frames_bucket_total{bucket="3_10"} 3877
telemt_desync_frames_bucket_total{bucket="gt_10"} 4888
telemt_pool_swap_total 207
telemt_pool_stale_pick_total 4
telemt_me_writer_removed_unexpected_total 39562
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 38944
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 3334563
telemt_user_connections_current{user="hello"} 846
telemt_user_octets_from_client{user="hello"} 57083890624 (53.16 GB)
telemt_user_octets_to_client{user="hello"} 1193217524249 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 223947.4 (62h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2610105
telemt_connections_bad_total 23507
telemt_handshake_timeouts_total 335786
telemt_upstream_connect_attempt_total 69124
telemt_upstream_connect_success_total 66617
telemt_upstream_connect_fail_total 2370
telemt_upstream_connect_attempts_per_request{bucket="1"} 68850
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2369
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20959
telemt_me_reconnect_attempts_total 61231
telemt_me_reconnect_success_total 48450
telemt_me_reader_eof_total 51913
telemt_me_idle_close_by_peer_total 51905
telemt_me_route_drop_no_conn_total 867540
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2040691
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4115
telemt_desync_full_logged_total 1353
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1681
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 192
telemt_me_writer_removed_unexpected_total 49271
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48425
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 821
telemt_user_connections_total{user="hello"} 2047097
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 30308626179 (28.23 GB)
telemt_user_octets_to_client{user="hello"} 730180970486 (680.03 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 93380.6 (25h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1063514
telemt_connections_bad_total 18098
telemt_handshake_timeouts_total 13776
telemt_upstream_connect_attempt_total 22760
telemt_upstream_connect_success_total 22134
telemt_upstream_connect_fail_total 626
telemt_upstream_connect_attempts_per_request{bucket="1"} 22760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 626
telemt_me_keepalive_timeout_total 1789
telemt_me_reconnect_attempts_total 82523
telemt_me_reconnect_success_total 17485
telemt_me_reader_eof_total 19925
telemt_me_idle_close_by_peer_total 19924
telemt_me_route_drop_no_conn_total 430338
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 984771
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2638
telemt_desync_full_logged_total 827
telemt_desync_suppressed_total 1811
telemt_desync_frames_bucket_total{bucket="1_2"} 947
telemt_desync_frames_bucket_total{bucket="3_10"} 939
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19676
telemt_me_refill_failed_total 2027
telemt_me_writer_restored_same_endpoint_total 17480
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2191
telemt_user_connections_total{user="hello"} 983970
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 17119548232 (15.94 GB)
telemt_user_octets_to_client{user="hello"} 331244923780 (308.50 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 97
```