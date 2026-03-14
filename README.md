# Server Metrics 2026-03-14 01:53:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 158103.2 (43h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4648032
telemt_connections_bad_total 39797
telemt_handshake_timeouts_total 108258
telemt_upstream_connect_attempt_total 33399
telemt_upstream_connect_success_total 33177
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 33399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 6705
telemt_me_reconnect_attempts_total 33105
telemt_me_reconnect_success_total 22967
telemt_me_reader_eof_total 24629
telemt_me_idle_close_by_peer_total 24628
telemt_me_route_drop_no_conn_total 1759574
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4261164
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16711
telemt_desync_full_logged_total 4505
telemt_desync_suppressed_total 12206
telemt_desync_frames_bucket_total{bucket="1_2"} 4175
telemt_desync_frames_bucket_total{bucket="3_10"} 6381
telemt_desync_frames_bucket_total{bucket="gt_10"} 6155
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 23614
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22954
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 647
telemt_user_connections_total{user="hello"} 4263020
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 62723454952 (58.42 GB)
telemt_user_octets_to_client{user="hello"} 1346180389385 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 57766.9 (16h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 686560
telemt_connections_bad_total 50959
telemt_handshake_timeouts_total 13046
telemt_upstream_connect_attempt_total 16072
telemt_upstream_connect_success_total 15823
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 16072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6734
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 2055
telemt_me_reconnect_attempts_total 14332
telemt_me_reconnect_success_total 10889
telemt_me_reader_eof_total 11561
telemt_me_idle_close_by_peer_total 11560
telemt_me_route_drop_no_conn_total 231461
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 551475
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1651
telemt_desync_full_logged_total 449
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 717
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11149
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10881
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 553426
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 5938297525 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 178024890112 (165.80 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 187723.7 (52h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3363499
telemt_connections_bad_total 34926
telemt_handshake_timeouts_total 223097
telemt_upstream_connect_attempt_total 42222
telemt_upstream_connect_success_total 42201
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10410
telemt_me_reconnect_attempts_total 37503
telemt_me_reconnect_success_total 32543
telemt_me_reader_eof_total 34552
telemt_me_idle_close_by_peer_total 34551
telemt_me_route_drop_no_conn_total 1153488
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2797522
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9225
telemt_desync_full_logged_total 3097
telemt_desync_suppressed_total 6128
telemt_desync_frames_bucket_total{bucket="1_2"} 1566
telemt_desync_frames_bucket_total{bucket="3_10"} 3342
telemt_desync_frames_bucket_total{bucket="gt_10"} 4317
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 33001
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32502
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 2796759
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 45071182368 (41.98 GB)
telemt_user_octets_to_client{user="hello"} 998949234401 (930.34 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 187726.3 (52h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2242634
telemt_connections_bad_total 22938
telemt_handshake_timeouts_total 243393
telemt_upstream_connect_attempt_total 58755
telemt_upstream_connect_success_total 56295
telemt_upstream_connect_fail_total 2322
telemt_upstream_connect_attempts_per_request{bucket="1"} 58480
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2321
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20407
telemt_me_reconnect_attempts_total 48960
telemt_me_reconnect_success_total 39929
telemt_me_reader_eof_total 42816
telemt_me_idle_close_by_peer_total 42809
telemt_me_route_drop_no_conn_total 769307
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1793516
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2583
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 40557
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 39905
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 1799437
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 27460263783 (25.57 GB)
telemt_user_octets_to_client{user="hello"} 665113070082 (619.43 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 57159.9 (15h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 689547
telemt_connections_bad_total 7891
telemt_handshake_timeouts_total 8644
telemt_upstream_connect_attempt_total 14387
telemt_upstream_connect_success_total 13987
telemt_upstream_connect_fail_total 400
telemt_upstream_connect_attempts_per_request{bucket="1"} 14387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 400
telemt_me_keepalive_timeout_total 1494
telemt_me_reconnect_attempts_total 43280
telemt_me_reconnect_success_total 11118
telemt_me_reader_eof_total 12407
telemt_me_idle_close_by_peer_total 12406
telemt_me_route_drop_no_conn_total 261698
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 641840
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1656
telemt_desync_full_logged_total 518
telemt_desync_suppressed_total 1138
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 511
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12220
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 11113
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1102
telemt_user_connections_total{user="hello"} 641727
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 10592617780 (9.87 GB)
telemt_user_octets_to_client{user="hello"} 209858881356 (195.45 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 22
```