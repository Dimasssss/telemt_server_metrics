# Server Metrics 2026-03-14 08:53:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 183267.7 (50h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5198011
telemt_connections_bad_total 46254
telemt_handshake_timeouts_total 117032
telemt_upstream_connect_attempt_total 38508
telemt_upstream_connect_success_total 38258
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 38508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 7423
telemt_me_reconnect_attempts_total 38029
telemt_me_reconnect_success_total 26817
telemt_me_reader_eof_total 28782
telemt_me_idle_close_by_peer_total 28781
telemt_me_route_drop_no_conn_total 1966925
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4766452
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18232
telemt_desync_full_logged_total 4970
telemt_desync_suppressed_total 13262
telemt_desync_frames_bucket_total{bucket="1_2"} 4516
telemt_desync_frames_bucket_total{bucket="3_10"} 6927
telemt_desync_frames_bucket_total{bucket="gt_10"} 6789
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 27557
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 26804
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 740
telemt_user_connections_total{user="hello"} 4767898
telemt_user_connections_current{user="hello"} 1641
telemt_user_octets_from_client{user="hello"} 73024476576 (68.01 GB)
telemt_user_octets_to_client{user="hello"} 1525116418089 (1.39 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 82931.4 (23h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 915543
telemt_connections_bad_total 54180
telemt_handshake_timeouts_total 17915
telemt_upstream_connect_attempt_total 22217
telemt_upstream_connect_success_total 21931
telemt_upstream_connect_fail_total 286
telemt_upstream_connect_attempts_per_request{bucket="1"} 22217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9714
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 286
telemt_me_keepalive_timeout_total 2180
telemt_me_reconnect_attempts_total 21980
telemt_me_reconnect_success_total 15757
telemt_me_reader_eof_total 16798
telemt_me_idle_close_by_peer_total 16797
telemt_me_route_drop_no_conn_total 304895
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 741664
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
telemt_me_writer_removed_unexpected_total 16177
telemt_me_refill_failed_total 188
telemt_me_writer_restored_same_endpoint_total 15749
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 420
telemt_user_connections_total{user="hello"} 743563
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 7865653205 (7.33 GB)
telemt_user_octets_to_client{user="hello"} 257315723636 (239.64 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 212888.1 (59h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3711938
telemt_connections_bad_total 44206
telemt_handshake_timeouts_total 244815
telemt_upstream_connect_attempt_total 48056
telemt_upstream_connect_success_total 48035
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 48056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10794
telemt_me_reconnect_attempts_total 42118
telemt_me_reconnect_success_total 37128
telemt_me_reader_eof_total 39420
telemt_me_idle_close_by_peer_total 39419
telemt_me_route_drop_no_conn_total 1273809
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3098514
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10115
telemt_desync_full_logged_total 3435
telemt_desync_suppressed_total 6680
telemt_desync_frames_bucket_total{bucket="1_2"} 1788
telemt_desync_frames_bucket_total{bucket="3_10"} 3670
telemt_desync_frames_bucket_total{bucket="gt_10"} 4657
telemt_pool_swap_total 200
telemt_me_writer_removed_unexpected_total 37642
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 37087
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 3097660
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 52502035944 (48.90 GB)
telemt_user_octets_to_client{user="hello"} 1106274781877 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 212890.9 (59h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2459088
telemt_connections_bad_total 23355
telemt_handshake_timeouts_total 301150
telemt_upstream_connect_attempt_total 66204
telemt_upstream_connect_success_total 63706
telemt_upstream_connect_fail_total 2361
telemt_upstream_connect_attempts_per_request{bucket="1"} 65930
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2360
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20584
telemt_me_reconnect_attempts_total 56458
telemt_me_reconnect_success_total 46092
telemt_me_reader_eof_total 49388
telemt_me_idle_close_by_peer_total 49381
telemt_me_route_drop_no_conn_total 823946
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1933259
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3970
telemt_desync_full_logged_total 1295
telemt_desync_suppressed_total 2675
telemt_desync_frames_bucket_total{bucket="1_2"} 1099
telemt_desync_frames_bucket_total{bucket="3_10"} 1630
telemt_desync_frames_bucket_total{bucket="gt_10"} 1241
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 46812
telemt_me_refill_failed_total 315
telemt_me_writer_restored_same_endpoint_total 46068
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 720
telemt_user_connections_total{user="hello"} 1939405
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 29039500015 (27.05 GB)
telemt_user_octets_to_client{user="hello"} 704608322302 (656.22 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 82323.9 (22h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 900354
telemt_connections_bad_total 11667
telemt_handshake_timeouts_total 11078
telemt_upstream_connect_attempt_total 20754
telemt_upstream_connect_success_total 20199
telemt_upstream_connect_fail_total 555
telemt_upstream_connect_attempts_per_request{bucket="1"} 20754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 555
telemt_me_keepalive_timeout_total 1638
telemt_me_reconnect_attempts_total 66629
telemt_me_reconnect_success_total 16094
telemt_me_reader_eof_total 18072
telemt_me_idle_close_by_peer_total 18071
telemt_me_route_drop_no_conn_total 343606
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 837953
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2171
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 1491
telemt_desync_frames_bucket_total{bucket="1_2"} 696
telemt_desync_frames_bucket_total{bucket="3_10"} 828
telemt_desync_frames_bucket_total{bucket="gt_10"} 647
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 17818
telemt_me_refill_failed_total 1574
telemt_me_writer_restored_same_endpoint_total 16089
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1724
telemt_user_connections_total{user="hello"} 837834
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 15154776620 (14.11 GB)
telemt_user_octets_to_client{user="hello"} 284562986000 (265.02 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 86
```