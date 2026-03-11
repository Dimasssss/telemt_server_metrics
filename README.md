# Server Metrics 2026-03-11 15:37:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 90622.7 (25h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2232688
telemt_connections_bad_total 39131
telemt_handshake_timeouts_total 52988
telemt_upstream_connect_attempt_total 18991
telemt_upstream_connect_success_total 18979
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9336
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4893
telemt_me_reconnect_attempts_total 32263
telemt_me_reconnect_success_total 14396
telemt_me_reader_eof_total 15628
telemt_me_idle_close_by_peer_total 15628
telemt_me_route_drop_no_conn_total 826543
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2041372
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10626
telemt_desync_full_logged_total 2883
telemt_desync_suppressed_total 7743
telemt_desync_frames_bucket_total{bucket="1_2"} 2633
telemt_desync_frames_bucket_total{bucket="3_10"} 4100
telemt_desync_frames_bucket_total{bucket="gt_10"} 3893
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 15114
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 14390
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 2039822
telemt_user_connections_current{user="hello"} 1496
telemt_user_octets_from_client{user="hello"} 27335349640 (25.46 GB)
telemt_user_octets_to_client{user="hello"} 579392410996 (539.60 GB)
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 90679.5 (25h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 827768
telemt_connections_bad_total 13530
telemt_handshake_timeouts_total 55890
telemt_upstream_connect_attempt_total 28819
telemt_upstream_connect_success_total 25861
telemt_upstream_connect_fail_total 2958
telemt_upstream_connect_attempts_per_request{bucket="1"} 28819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11587
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2958
telemt_me_keepalive_timeout_total 2557
telemt_me_reconnect_attempts_total 20456
telemt_me_reconnect_success_total 18363
telemt_me_reader_eof_total 19426
telemt_me_idle_close_by_peer_total 19423
telemt_me_route_drop_no_conn_total 324473
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 704018
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2896
telemt_desync_full_logged_total 921
telemt_desync_suppressed_total 1975
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1042
telemt_desync_frames_bucket_total{bucket="gt_10"} 962
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18628
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 18340
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 706496
telemt_user_connections_current{user="hello"} 566
telemt_user_octets_from_client{user="hello"} 8204986338 (7.64 GB)
telemt_user_octets_to_client{user="hello"} 199739114888 (186.02 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 90679.3 (25h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1436478
telemt_connections_bad_total 8662
telemt_handshake_timeouts_total 124248
telemt_upstream_connect_attempt_total 23838
telemt_upstream_connect_success_total 23549
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 23838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 1587
telemt_me_reconnect_attempts_total 37606
telemt_me_reconnect_success_total 17906
telemt_me_reader_eof_total 19327
telemt_me_idle_close_by_peer_total 19327
telemt_me_route_drop_no_conn_total 523111
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1251174
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3310
telemt_desync_full_logged_total 982
telemt_desync_suppressed_total 2328
telemt_desync_frames_bucket_total{bucket="1_2"} 815
telemt_desync_frames_bucket_total{bucket="3_10"} 1254
telemt_desync_frames_bucket_total{bucket="gt_10"} 1241
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18766
telemt_me_refill_failed_total 611
telemt_me_writer_restored_same_endpoint_total 17895
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 860
telemt_user_connections_total{user="hello"} 1250893
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 15061644741 (14.03 GB)
telemt_user_octets_to_client{user="hello"} 376489343901 (350.63 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 90679.9 (25h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1030730
telemt_connections_bad_total 77936
telemt_handshake_timeouts_total 100648
telemt_upstream_connect_attempt_total 24255
telemt_upstream_connect_success_total 24255
telemt_upstream_connect_attempts_per_request{bucket="1"} 24255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1013
telemt_me_reconnect_attempts_total 20811
telemt_me_reconnect_success_total 19736
telemt_me_reader_eof_total 20925
telemt_me_idle_close_by_peer_total 20924
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 337366
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 823958
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1733
telemt_desync_full_logged_total 665
telemt_desync_suppressed_total 1068
telemt_desync_frames_bucket_total{bucket="1_2"} 622
telemt_desync_frames_bucket_total{bucket="3_10"} 610
telemt_desync_frames_bucket_total{bucket="gt_10"} 501
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 19977
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19706
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 823286
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 9839288112 (9.16 GB)
telemt_user_octets_to_client{user="hello"} 242879691288 (226.20 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 90679.3 (25h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1140468
telemt_connections_bad_total 6939
telemt_handshake_timeouts_total 11482
telemt_upstream_connect_attempt_total 24531
telemt_upstream_connect_success_total 24422
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 24531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11755
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 198
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1951
telemt_me_reconnect_attempts_total 23851
telemt_me_reconnect_success_total 19762
telemt_me_reader_eof_total 20834
telemt_me_idle_close_by_peer_total 20834
telemt_me_route_drop_no_conn_total 406260
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1037245
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4002
telemt_desync_full_logged_total 1454
telemt_desync_suppressed_total 2548
telemt_desync_frames_bucket_total{bucket="1_2"} 1355
telemt_desync_frames_bucket_total{bucket="3_10"} 1497
telemt_desync_frames_bucket_total{bucket="gt_10"} 1150
telemt_pool_swap_total 60
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20144
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19762
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 1036952
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 15275499131 (14.23 GB)
telemt_user_octets_to_client{user="hello"} 362978961398 (338.05 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 97
```