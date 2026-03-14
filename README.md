# Server Metrics 2026-03-14 10:20:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 188494.7 (52h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5405117
telemt_connections_bad_total 55919
telemt_handshake_timeouts_total 120063
telemt_upstream_connect_attempt_total 39632
telemt_upstream_connect_success_total 39376
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 39632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_keepalive_timeout_total 7588
telemt_me_reconnect_attempts_total 40127
telemt_me_reconnect_success_total 27661
telemt_me_reader_eof_total 29690
telemt_me_idle_close_by_peer_total 29689
telemt_me_route_drop_no_conn_total 2042841
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4951866
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18908
telemt_desync_full_logged_total 5172
telemt_desync_suppressed_total 13736
telemt_desync_frames_bucket_total{bucket="1_2"} 4643
telemt_desync_frames_bucket_total{bucket="3_10"} 7203
telemt_desync_frames_bucket_total{bucket="gt_10"} 7062
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 28455
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 27648
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 794
telemt_user_connections_total{user="hello"} 4953311
telemt_user_connections_current{user="hello"} 1697
telemt_user_octets_from_client{user="hello"} 75921540036 (70.71 GB)
telemt_user_octets_to_client{user="hello"} 1577543758085 (1.43 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 88158.8 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 994675
telemt_connections_bad_total 57130
telemt_handshake_timeouts_total 21418
telemt_upstream_connect_attempt_total 23095
telemt_upstream_connect_success_total 22804
telemt_upstream_connect_fail_total 291
telemt_upstream_connect_attempts_per_request{bucket="1"} 23095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 291
telemt_me_keepalive_timeout_total 2254
telemt_me_reconnect_attempts_total 26277
telemt_me_reconnect_success_total 16402
telemt_me_reader_eof_total 17591
telemt_me_idle_close_by_peer_total 17590
telemt_me_route_drop_no_conn_total 333788
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 812020
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2283
telemt_desync_full_logged_total 714
telemt_desync_suppressed_total 1569
telemt_desync_frames_bucket_total{bucket="1_2"} 534
telemt_desync_frames_bucket_total{bucket="3_10"} 970
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 16945
telemt_me_refill_failed_total 302
telemt_me_writer_restored_same_endpoint_total 16394
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 543
telemt_user_connections_total{user="hello"} 813910
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 8843404817 (8.24 GB)
telemt_user_octets_to_client{user="hello"} 284064538636 (264.56 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 218115.3 (60h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3843683
telemt_connections_bad_total 45728
telemt_handshake_timeouts_total 254152
telemt_upstream_connect_attempt_total 49261
telemt_upstream_connect_success_total 49240
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 49261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 11011
telemt_me_reconnect_attempts_total 43055
telemt_me_reconnect_success_total 38056
telemt_me_reader_eof_total 40395
telemt_me_idle_close_by_peer_total 40394
telemt_me_route_drop_no_conn_total 1319456
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3211830
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10309
telemt_desync_full_logged_total 3505
telemt_desync_suppressed_total 6804
telemt_desync_frames_bucket_total{bucket="1_2"} 1865
telemt_desync_frames_bucket_total{bucket="3_10"} 3730
telemt_desync_frames_bucket_total{bucket="gt_10"} 4714
telemt_pool_swap_total 203
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 38586
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 38015
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 3210970
telemt_user_connections_current{user="hello"} 1003
telemt_user_octets_from_client{user="hello"} 54453878208 (50.71 GB)
telemt_user_octets_to_client{user="hello"} 1151934771657 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 218117.9 (60h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2534445
telemt_connections_bad_total 23405
telemt_handshake_timeouts_total 320719
telemt_upstream_connect_attempt_total 67615
telemt_upstream_connect_success_total 65110
telemt_upstream_connect_fail_total 2368
telemt_upstream_connect_attempts_per_request{bucket="1"} 67341
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26075
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2367
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20740
telemt_me_reconnect_attempts_total 58876
telemt_me_reconnect_success_total 47220
telemt_me_reader_eof_total 50602
telemt_me_idle_close_by_peer_total 50594
telemt_me_route_drop_no_conn_total 845508
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1984505
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4044
telemt_desync_full_logged_total 1322
telemt_desync_suppressed_total 2722
telemt_desync_frames_bucket_total{bucket="1_2"} 1139
telemt_desync_frames_bucket_total{bucket="3_10"} 1653
telemt_desync_frames_bucket_total{bucket="gt_10"} 1252
telemt_pool_swap_total 189
telemt_me_writer_removed_unexpected_total 47992
telemt_me_refill_failed_total 355
telemt_me_writer_restored_same_endpoint_total 47196
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 772
telemt_user_connections_total{user="hello"} 1990711
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 29706015063 (27.67 GB)
telemt_user_octets_to_client{user="hello"} 717604883750 (668.32 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 87551.1 (24h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 980867
telemt_connections_bad_total 16038
telemt_handshake_timeouts_total 12888
telemt_upstream_connect_attempt_total 22042
telemt_upstream_connect_success_total 21450
telemt_upstream_connect_fail_total 592
telemt_upstream_connect_attempts_per_request{bucket="1"} 22042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 592
telemt_me_keepalive_timeout_total 1695
telemt_me_reconnect_attempts_total 73882
telemt_me_reconnect_success_total 17069
telemt_me_reader_eof_total 19255
telemt_me_idle_close_by_peer_total 19254
telemt_me_route_drop_no_conn_total 377581
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 908177
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2419
telemt_desync_full_logged_total 756
telemt_desync_suppressed_total 1663
telemt_desync_frames_bucket_total{bucket="1_2"} 820
telemt_desync_frames_bucket_total{bucket="3_10"} 896
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19002
telemt_me_refill_failed_total 1770
telemt_me_writer_restored_same_endpoint_total 17064
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1933
telemt_user_connections_total{user="hello"} 908118
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 16024138356 (14.92 GB)
telemt_user_octets_to_client{user="hello"} 305623405512 (284.63 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 95
```