# Server Metrics 2026-03-14 13:09:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 198621.4 (55h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5785707
telemt_connections_bad_total 67951
telemt_handshake_timeouts_total 127778
telemt_upstream_connect_attempt_total 41570
telemt_upstream_connect_success_total 41302
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 41570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 7903
telemt_me_reconnect_attempts_total 49367
telemt_me_reconnect_success_total 29085
telemt_me_reader_eof_total 31392
telemt_me_idle_close_by_peer_total 31391
telemt_me_route_drop_no_conn_total 2194608
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5302908
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20501
telemt_desync_full_logged_total 5620
telemt_desync_suppressed_total 14881
telemt_desync_frames_bucket_total{bucket="1_2"} 4928
telemt_desync_frames_bucket_total{bucket="3_10"} 7788
telemt_desync_frames_bucket_total{bucket="gt_10"} 7785
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 30142
telemt_me_refill_failed_total 628
telemt_me_writer_restored_same_endpoint_total 29072
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 1057
telemt_user_connections_total{user="hello"} 5304564
telemt_user_connections_current{user="hello"} 1868
telemt_user_octets_from_client{user="hello"} 82761275072 (77.08 GB)
telemt_user_octets_to_client{user="hello"} 1691891575633 (1.54 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 98285.1 (27h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1141092
telemt_connections_bad_total 59792
telemt_handshake_timeouts_total 27708
telemt_upstream_connect_attempt_total 25628
telemt_upstream_connect_success_total 25315
telemt_upstream_connect_fail_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 25624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 271
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 309
telemt_me_keepalive_timeout_total 2451
telemt_me_reconnect_attempts_total 40447
telemt_me_reconnect_success_total 17573
telemt_me_reader_eof_total 19180
telemt_me_idle_close_by_peer_total 19179
telemt_me_route_drop_no_conn_total 386119
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 940274
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2614
telemt_desync_full_logged_total 825
telemt_desync_suppressed_total 1789
telemt_desync_frames_bucket_total{bucket="1_2"} 681
telemt_desync_frames_bucket_total{bucket="3_10"} 1093
telemt_desync_frames_bucket_total{bucket="gt_10"} 840
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18536
telemt_me_refill_failed_total 708
telemt_me_writer_restored_same_endpoint_total 17565
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 963
telemt_user_connections_total{user="hello"} 942983
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 10417027200 (9.70 GB)
telemt_user_octets_to_client{user="hello"} 337488958933 (314.31 GB)
telemt_user_msgs_from_client{user="hello"} 9054
telemt_user_msgs_to_client{user="hello"} 20524
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 228241.7 (63h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4104710
telemt_connections_bad_total 48216
telemt_handshake_timeouts_total 286337
telemt_upstream_connect_attempt_total 51401
telemt_upstream_connect_success_total 51379
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 51401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 11370
telemt_me_reconnect_attempts_total 45696
telemt_me_reconnect_success_total 39686
telemt_me_reader_eof_total 42150
telemt_me_idle_close_by_peer_total 42148
telemt_me_route_drop_no_conn_total 1411196
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3431616
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10966
telemt_desync_full_logged_total 3698
telemt_desync_suppressed_total 7268
telemt_desync_frames_bucket_total{bucket="1_2"} 2019
telemt_desync_frames_bucket_total{bucket="3_10"} 3949
telemt_desync_frames_bucket_total{bucket="gt_10"} 4998
telemt_pool_swap_total 210
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 40274
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39645
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 3430752
telemt_user_connections_current{user="hello"} 992
telemt_user_octets_from_client{user="hello"} 58394820824 (54.38 GB)
telemt_user_octets_to_client{user="hello"} 1224044552049 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 228244.3 (63h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2672070
telemt_connections_bad_total 23532
telemt_handshake_timeouts_total 350709
telemt_upstream_connect_attempt_total 70190
telemt_upstream_connect_success_total 67680
telemt_upstream_connect_fail_total 2373
telemt_upstream_connect_attempts_per_request{bucket="1"} 69916
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2372
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21022
telemt_me_reconnect_attempts_total 62076
telemt_me_reconnect_success_total 49288
telemt_me_reader_eof_total 52789
telemt_me_idle_close_by_peer_total 52781
telemt_me_route_drop_no_conn_total 884180
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2084390
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4124
telemt_desync_full_logged_total 1356
telemt_desync_suppressed_total 2768
telemt_desync_frames_bucket_total{bucket="1_2"} 1173
telemt_desync_frames_bucket_total{bucket="3_10"} 1688
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 195
telemt_me_writer_removed_unexpected_total 50118
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 49263
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 830
telemt_user_connections_total{user="hello"} 2090993
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 30863186719 (28.74 GB)
telemt_user_octets_to_client{user="hello"} 742457652782 (691.47 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 97677.8 (27h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1125793
telemt_connections_bad_total 18205
telemt_handshake_timeouts_total 14316
telemt_upstream_connect_attempt_total 23194
telemt_upstream_connect_success_total 22518
telemt_upstream_connect_fail_total 676
telemt_upstream_connect_attempts_per_request{bucket="1"} 23194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 676
telemt_me_keepalive_timeout_total 1832
telemt_me_reconnect_attempts_total 89564
telemt_me_reconnect_success_total 17646
telemt_me_reader_eof_total 20301
telemt_me_idle_close_by_peer_total 20300
telemt_me_route_drop_no_conn_total 453507
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1043286
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2756
telemt_desync_full_logged_total 869
telemt_desync_suppressed_total 1887
telemt_desync_frames_bucket_total{bucket="1_2"} 1001
telemt_desync_frames_bucket_total{bucket="3_10"} 966
telemt_desync_frames_bucket_total{bucket="gt_10"} 789
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 20052
telemt_me_refill_failed_total 2242
telemt_me_writer_restored_same_endpoint_total 17641
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2406
telemt_user_connections_total{user="hello"} 1042487
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 18183051784 (16.93 GB)
telemt_user_octets_to_client{user="hello"} 353693583916 (329.40 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 100
```