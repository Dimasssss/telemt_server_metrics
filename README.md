# Server Metrics 2026-03-11 18:10:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 99816.9 (27h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2529814
telemt_connections_bad_total 47969
telemt_handshake_timeouts_total 56333
telemt_upstream_connect_attempt_total 21077
telemt_upstream_connect_success_total 21065
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 21077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5291
telemt_me_reconnect_attempts_total 33905
telemt_me_reconnect_success_total 16025
telemt_me_reader_eof_total 17327
telemt_me_idle_close_by_peer_total 17327
telemt_me_route_drop_no_conn_total 943304
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2314088
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11805
telemt_desync_full_logged_total 3252
telemt_desync_suppressed_total 8553
telemt_desync_frames_bucket_total{bucket="1_2"} 2914
telemt_desync_frames_bucket_total{bucket="3_10"} 4565
telemt_desync_frames_bucket_total{bucket="gt_10"} 4326
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16763
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 16019
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 2312531
telemt_user_connections_current{user="hello"} 1223
telemt_user_octets_from_client{user="hello"} 33073827408 (30.80 GB)
telemt_user_octets_to_client{user="hello"} 653948700772 (609.04 GB)
telemt_user_unique_ips_current{user="hello"} 361
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 99873.6 (27h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 949081
telemt_connections_bad_total 16357
telemt_handshake_timeouts_total 84470
telemt_upstream_connect_attempt_total 31116
telemt_upstream_connect_success_total 28150
telemt_upstream_connect_fail_total 2966
telemt_upstream_connect_attempts_per_request{bucket="1"} 31116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2041
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2966
telemt_me_keepalive_timeout_total 2813
telemt_me_reconnect_attempts_total 22302
telemt_me_reconnect_success_total 20192
telemt_me_reader_eof_total 21369
telemt_me_idle_close_by_peer_total 21366
telemt_me_route_drop_no_conn_total 358397
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 790991
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3110
telemt_desync_full_logged_total 999
telemt_desync_suppressed_total 2111
telemt_desync_frames_bucket_total{bucket="1_2"} 961
telemt_desync_frames_bucket_total{bucket="3_10"} 1110
telemt_desync_frames_bucket_total{bucket="gt_10"} 1039
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 20474
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 20169
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 793453
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 9575788530 (8.92 GB)
telemt_user_octets_to_client{user="hello"} 225925081636 (210.41 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 99873.7 (27h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1623252
telemt_connections_bad_total 9994
telemt_handshake_timeouts_total 130290
telemt_upstream_connect_attempt_total 25825
telemt_upstream_connect_success_total 25501
telemt_upstream_connect_fail_total 324
telemt_upstream_connect_attempts_per_request{bucket="1"} 25825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11647
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 324
telemt_me_keepalive_timeout_total 1940
telemt_me_reconnect_attempts_total 45403
telemt_me_reconnect_success_total 19398
telemt_me_reader_eof_total 21061
telemt_me_idle_close_by_peer_total 21061
telemt_me_route_drop_no_conn_total 591540
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1420991
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3868
telemt_desync_full_logged_total 1129
telemt_desync_suppressed_total 2739
telemt_desync_frames_bucket_total{bucket="1_2"} 919
telemt_desync_frames_bucket_total{bucket="3_10"} 1471
telemt_desync_frames_bucket_total{bucket="gt_10"} 1478
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 20480
telemt_me_refill_failed_total 807
telemt_me_writer_restored_same_endpoint_total 19386
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1082
telemt_user_connections_total{user="hello"} 1420676
telemt_user_connections_current{user="hello"} 909
telemt_user_octets_from_client{user="hello"} 17604263261 (16.40 GB)
telemt_user_octets_to_client{user="hello"} 432315356393 (402.63 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 99874.0 (27h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1158661
telemt_connections_bad_total 77991
telemt_handshake_timeouts_total 107667
telemt_upstream_connect_attempt_total 26927
telemt_upstream_connect_success_total 26927
telemt_upstream_connect_attempts_per_request{bucket="1"} 26927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1401
telemt_me_reconnect_attempts_total 26553
telemt_me_reconnect_success_total 21947
telemt_me_reader_eof_total 23310
telemt_me_idle_close_by_peer_total 23309
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 385633
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 938947
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1990
telemt_desync_full_logged_total 758
telemt_desync_suppressed_total 1232
telemt_desync_frames_bucket_total{bucket="1_2"} 718
telemt_desync_frames_bucket_total{bucket="3_10"} 685
telemt_desync_frames_bucket_total{bucket="gt_10"} 587
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 22324
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21914
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 377
telemt_user_connections_total{user="hello"} 938223
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 11240192400 (10.47 GB)
telemt_user_octets_to_client{user="hello"} 284940466204 (265.37 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 4550.0 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81067
telemt_connections_bad_total 315
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 1306
telemt_upstream_connect_success_total 1306
telemt_upstream_connect_attempts_per_request{bucket="1"} 1306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 1047
telemt_me_reconnect_success_total 1038
telemt_me_reader_eof_total 1048
telemt_me_idle_close_by_peer_total 1048
telemt_me_route_drop_no_conn_total 27022
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75773
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 176
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1046
telemt_me_writer_restored_same_endpoint_total 1016
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 75768
telemt_user_connections_current{user="hello"} 677
telemt_user_octets_from_client{user="hello"} 6065370680 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 28158493964 (26.22 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 86
```